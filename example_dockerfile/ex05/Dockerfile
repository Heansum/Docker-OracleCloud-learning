FROM ubuntu:18.04

LABEL title="My Ubuntu"

ARG MESSAGE="complete"

RUN adduser --disabled-password --gecos "" heansum
RUN whoami 

USER heansum
RUN whoami

RUN echo $MESSAGE



