FROM rpi-trusty
MAINTAINER de13 <stephane.beuret@data-essential.com>
ENV DEBIAN_FRONTEND noninteractive
ADD sources.list /etc/apt/sources.list
RUN apt-get update -y && \
    apt-get install -y ca-certificates openssl
