# docker-node-demo
A simple demo to use node in docker container

Use two different command: the native `docker` and amazing tool `docker-compose`
 
## Description
Aim to create a docker container which runs a node server listening to 8080, expose to 8081

## How to use
Run the following command, then visit `127.0.0.1:8081` you should see "hello world!"
#### Case `docker`
```sh
$ cd docker-native
$ docker build -t nodedocker_test . && docker run -d -p 8080:8081 -v $(pwd)/../src:/src nodedocker_test
```
#### Case `docker-compose`
```sh
$ cd docker-compose
$ docker-compose up -d
```
