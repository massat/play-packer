Described only for OSX.

## Install packer

```
$ brew install packer
```

## Install docker and create a vm

```
$ brew install docker
$ brew install docker-engine

$ docker-machine create --driver virtualbox default
$ eval "$(docker-machine env default)"
```

## build a docker image.

```
$ packer build example.json
```
