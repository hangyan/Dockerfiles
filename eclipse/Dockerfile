FROM ubuntu:14.04

MAINTAINER Hang Yan yanhangyhy@gmail.com

RUN sed -i "s/archive.ubuntu.com/mirrors.ustc.edu.cn/" /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y eclipse



CMD /usr/bin/eclipse

   

