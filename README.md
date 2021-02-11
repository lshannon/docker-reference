# Basic Docker Reference

The following are basic docker commands for local development use. The sudo is added so they can be copied and pasted into a Ubuntu terminal environment.

## Terminology

Image: The template for the Container (Dockerfile)
Container: Built with the Docker Build command.

## See All Containers

```shell

sudo docker ps -a

```

## See All Images

```shell

sudo docker images

```

## Stop A Running Container

```shell

sudo docker stop <Container ID>

```

## Remove A Container

```shell

sudo docker rm <Container ID>

```
