# Howtocodewell Podcast

## Requirements
- Jeykell
- Docker
- Docker Machine
- Docker Compose

## Install

Build the Docker machine, image and container
```
$ docker-machine create howtocodewell.fm
$ docker-machine env howtocodewell.fm
$ eval $(docker-machine env howtocodewell.fm)
$ docker-compose up -d --bulid
```

Get the IP of the Docker Machine
```
$ docker-machine ip howtocodewell.fm
```
Now go to the IP in the browser
