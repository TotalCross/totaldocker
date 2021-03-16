FROM amd64/ubuntu:bionic

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        cmake \
        ninja-build \
        build-essential \
        libsdl2-dev \
        libfontconfig1-dev \
        git \
        ca-certificates; \
    apt-get clean

ENV BUILD_FOLDER /build

WORKDIR ${BUILD_FOLDER}
