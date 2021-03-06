# Docker

See Docker [homepage](https://www.docker.com/) for more information.

NOTE! Don't use [Docker for Mac](docker_for_mac.md) at the same time!

## Install

OSX/macOS using [Brew](brew.md)

```
$ brew install docker docker-compose docker-machine
```

## Create the default machine

Create the default VM with [VMWare Fusion](vmware_fusion.md) driver

```
$ docker-machine create default -d vmwarefusion && eval $(docker-machine env default)
```

## Commandline

Check Docker version

```
$ docker version
```

Check Docker containers

```
$ docker ps
```

Get docker machine IP

```
$ docker-machine ip
```
