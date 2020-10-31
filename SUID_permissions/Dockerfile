FROM ubuntu:18.04

LABEL maintainer="equinockx git:moisestapia"
LABEL twitter="equinockx"
LABEL git="https://github.com/MoisesTapia"
LABEL repo="https://github.com/MoisesTapia/Intro-To-Hack"

RUN apt-get update && apt-get upgrade -y

RUN echo "root:root" | chpasswd

RUN useradd pepito

RUN echo "pepito:pepepito" | chpasswd

RUN mkdir /home/pepito

USER pepito

EXPOSE 22