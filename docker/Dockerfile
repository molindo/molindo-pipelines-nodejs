FROM debian:buster-slim

RUN apt-get update \
        && apt-get install -y git curl jshon python-pip python-dev \
        && pip install awscli \
        && apt-get clean \
        && rm -rf /var/lib/apt/lists/*

ADD bin /usr/local/bin
