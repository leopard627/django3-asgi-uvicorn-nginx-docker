# django3-asgi-uvicorn-nginx-docker
django3-asgi-uvicorn-nginx-docker exmaple 


### run without docker
```
DJANGO_SETTINGS_MODULE=django3_uvicorn.settings.dev uvicorn django3_uvicorn.asgi:application
```

### build docker & run 
```
docker build -t django3_uvicorn:0.0.1 .

docker run -it -d --rm -p 8080:80 django3_uvicorn:0.0.1
```
