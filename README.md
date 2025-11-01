# MyTutorial-Docker

## Get that Linux feeling - on Windows
https://www.cygwin.com/

## Check docker installed
```
% docker
% docker container run hello-world
```

## Example-1
```
% docker image pull zhamri/hello-world:1.0
% docker container run zhamri/hello-world:1.0
```

## Example-2
```
% docker image pull zhamri/hello-world-boot:latest
% docker container run -d -p 80:8080 zhamri/hello-world-boot:latest
```

## Docker Hub
```
https://hub.docker.com/
https://hub.docker.com/repository/docker/zhamri/hello-world/general
```

## List all running container
```
% docker container ls
```
