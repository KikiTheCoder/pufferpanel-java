FROM openjdk:11.0.12-slim-buster

RUN adduser -D -h /server pufferd
WORKDIR /server

RUN apt-get update && apt-get install -y git
# Add any additional commands here

USER pufferd
ENV HOME /server