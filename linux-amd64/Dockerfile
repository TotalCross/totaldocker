FROM amd64/ubuntu:bionic

RUN apt-get update
RUN apt-get install -y cmake ninja-build libsdl2-dev libfontconfig1-dev
ENV BUILD_FOLDER /build

WORKDIR ${BUILD_FOLDER}