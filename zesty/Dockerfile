FROM ubuntu:zesty

RUN set -ex; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
        build-essential \
        debhelper \
        devscripts \
        fakeroot; \
    rm -rf /var/lib/apt/lists/*
