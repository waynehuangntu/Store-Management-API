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
The API will allow clients to:

* Create and retrieve information about stores.
* Create, retrieve, search for, update, and delete items in those stores.
* Create tags and link them to items; and search for items with specific tags.
* Add user authentication to the client apps using the API.
