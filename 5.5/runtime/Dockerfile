FROM iron/python:2
MAINTAINER Yu You <youyu.youyu@gmail.com>

# A base image for QT 5.5

RUN echo "@testing http://nl.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories && \
apk update && apk upgrade \
  && apk add nano qt5-qtbase qt5-qtmultimedia \
  && rm -rf /var/cache/apk/*

