docker-apt-file
===============

Dockerfile for apt-file of Ubuntu

Docker image
------------

Pull the image from [Docker Hub](https://hub.docker.com/r/dceoy/apt-file/).

```sh
$ docker pull dceoy/apt-file
```

Usage
-----

Search files in packages

```sh
$ docker container run --rm dceoy/apt-file search <pattern>
```
