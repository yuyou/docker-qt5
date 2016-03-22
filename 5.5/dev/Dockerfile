FROM iron/python:2
MAINTAINER Yu You <youyu.youyu@gmail.com>
# see https://github.com/yuyou/docker-qt5/tree/master
# A base image for QT 5.5 development

RUN echo "@testing http://nl.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories && \
apk update && apk upgrade \
  && apk add --update alpine-sdk nano qt5-qtbase qt5-qtmultimedia-dev qt5-qttools-dev \
  && rm -rf /var/cache/apk/*

