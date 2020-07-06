# docker-devcontainer-java

VSCode devcontainer based on openjdk:11-jdk, with Powershell and tools

[![DockerPulls](https://img.shields.io/docker/pulls/tolgabalci/devcontainer-java.svg)](https://registry.hub.docker.com/r/tolgabalci/devcontainer-java/)
[![DockerStars](https://img.shields.io/docker/stars/tolgabalci/devcontainer-java.svg)](https://registry.hub.docker.com/r/tolgabalci/devcontainer-java/)

This repository contains a Docker file to build a Docker image for a developer environment. Compatible as a VSCode Dev Container.

## Pull the image from Docker Repository

```
docker pull tolgabalci/devcontainer-java
```

## Run the image from Docker Repository

- You can use this image for your VSCode Dev Container or
- You can run it directly:

```
docker run -it tolgabalci/devcontainer-java
```

## Build your own version of the image

```
docker build --rm -t <hub-user>/devcontainer-java .
```

## Push your own version of the image to Docker Hub

\$ docker push <hub-user>/devcontainer-java
