# CONTRINUTING

## How to run the DockerFile locally
* Build docker image
```
docker build -t flask-smorest-api .
```

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" flask-smorest-api sh -c "flask run --host 0.0.0.0"
```
