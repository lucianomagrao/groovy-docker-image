# Groovy docker image

[![Docker Stars](https://img.shields.io/docker/stars/leslau/groovy.svg)](https://hub.docker.com/r/leslau/groovy/) [![Docker Pulls](https://img.shields.io/docker/pulls/leslau/groovy.svg)](https://hub.docker.com/r/leslau/groovy/) [![Docker Automated buil](https://img.shields.io/docker/automated/leslau/groovy.svg)](https://hub.docker.com/r/leslau/groovy/) [![ImageLayers Size](https://img.shields.io/imagelayers/image-size/leslau/groovy/latest.svg)]()

This image contains [Groovy](http://groovy-lang.org/) and uses [java:8-alpine](https://hub.docker.com/_/java/) as base.

## Tags

* [latest, 2.5.2-alpine](https://hub.docker.com/r/leslau/groovy/)
* [2.4.7-alpine](https://hub.docker.com/r/leslau/groovy/)

## Usage

```
docker run -it -v $(pwd):/data leslau/groovy /data/foo.groovy
```
