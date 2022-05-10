# Laravel docker image
Is my own implementation to my Laravel API projects. Execute composer.
```
userId: 1000
user: laravel
php: 8.0
```

## Build the image and name it
```shell
docker build --tag laravel-docker-image .
```
## Login to docker hub
```shell
docker login
```
## Tag the image
```shell
docker tag laravel-docker-image {DOCKER_USERNAME}/laravel-docker-image:1.0
```
## Push the image to repository
```shell
docker push {DOCKER_USERNAME}/laravel-docker-image:1.0
```
## Verify repository exists
```shell
https://hub.docker.com/r/{DOCKER_USERNAME}/laravel-docker-image
```