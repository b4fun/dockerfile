# b4fun/dockerize-ubuntu

[![Docker Automated build](https://img.shields.io/docker/automated/b4fun/dockerize-ubuntu.svg)](https://hub.docker.com/r/b4fun/dockerize-ubuntu/)

## tags

- 0.6.0

## usage

```
FROM b4fun/dockerize-ubuntu as dockerize

COPY --from=dockerize /usr/local/bin/dockerize /usr/local/bin
```
