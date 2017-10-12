# ####
# ubuntu 16.04
#
# build:
#   docker build --force-rm=ture -t cincrain/ubuntu:16.04 .
# ####

FROM ubuntu:16.04

MAINTAINER cincrain <cincrain@gmail.com>

ENV DEBIAN_FRONTEND noninteractive

RUN echo "20171011"
# RUN sed -i -e 's/archive.ubuntu.com/ftp.daumkakao.com/g' /etc/apt/sources.list
RUN apt-get update
RUN apt-get -y upgrade

RUN apt-get install -qq -y locales
RUN locale-gen en_US.UTF-8
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8
