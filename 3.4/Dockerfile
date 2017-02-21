FROM mongo:3.4

MAINTAINER Ilya Mochalov <chrootsu@gmail.com>

RUN apt-get update && apt-get install -qy paxctl \
	&& paxctl -cm /usr/bin/mongo \
	&& rm -rf /var/lib/apt/lists/*
