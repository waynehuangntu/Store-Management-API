# CONTRINUTING

## How to run the DockerFile locally
* Build docker image
```
docker build -t flask-smorest-api .
```
* Run in docker contatiner
```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" flask-smorest-api sh -c "flask run --host 0.0.0.0"
```
## Project Overview
Key Accomplishments:

* Developed a RESTful API with Python and Flask, enabling clients to interact with the system programmatically and perform various store and item management tasks.
* Designed a PostgreSQL and SQLite database schema to securely store store/item data, ensuring data integrity and efficient querying.
* Implemented comprehensive features allowing clients to create, retrieve, search for, update, and delete stores and items within those stores.
* Incorporated a tagging system, allowing users to create tags and associate them with specific items. Additionally, clients could search for items using specific tags.
* Enhanced security by implementing user authentication using JSON Web Tokens (JWT), ensuring secure access to the API and user-specific functionality.
* Utilized Flask extensions to streamline the development process, reducing code complexity and improving maintainability.
* Employed Docker to containerize the API, enhancing reliability and making deployment across different environments consistent and seamless.