# url_shortener
URL Shortener written in Django

Deploying with Docker
1. Build image:
```
docker build -t <image_name> .
```
2. Run container:
```
docker run -dp 8000:8000 <image_name>
```
