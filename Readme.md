Golang Build Image
==================

[
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/mantikai/golang_build)
](https://cloud.docker.com/u/mantikai/repository/docker/mantikai/golang_build)

Internally used image for building go applications.

It differs from golang in the following way

* Installed protobuf compiler for golang 
* Using Net DNS for name resolution
* Different work directory


Tag Names
---------

The docker image tag is generated from the git tag.

The Git tag should match the Golang base image version, e.g. `1.13.1-1`. The last number is the revision, if something got changed.

The docker build service will automatically build the image.
