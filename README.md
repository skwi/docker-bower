# Docker bower container

## Supported tags and respective `Dockerfile` links
+ `1.5.2`, `latest` ([Dockerfile](https://github.com/skwi/docker-bower/blob/master/Dockerfile))

## Installation
1. Install [Docker](https://www.docker.com/).
2. Download an automated build from [the Docker Hub Registry](https://hub.docker.com): `docker pull skwi/docker-bower`

## How to use this image

Run any bower command
```sh
$ docker run --rm -v $(pwd):/data skwi/docker-bower
```
This will call the `bower` command int the `/data` folder of the container. You can off course call the `bower` command with different options 
```sh
$ docker run --rm -v $(pwd):/data skwi/docker-bower install jquery
```

## Issues
If you have any problems with or questions about this image, please contact us through a GitHub issue.

## Contributing
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.