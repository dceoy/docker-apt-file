docker-apt-file
===============

Dockerfile for apt-file of Ubuntu

[![CI/CD](https://github.com/dceoy/docker-apt-file/actions/workflows/ci.yml/badge.svg)](https://github.com/dceoy/docker-apt-file/actions/workflows/ci.yml)

Docker image
------------

Pull the image from [Docker Hub](https://hub.docker.com/r/dceoy/apt-file/).

```sh
$ docker image pull dceoy/apt-file
```

Usage
-----

Search files in packages

```sh
$ docker container run --rm dceoy/apt-file search <pattern>
```
