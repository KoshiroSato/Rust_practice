FROM rust:latest

RUN apt-get update -y && apt-get upgrade -y &&\
  apt-get install curl vim git -y &&\
  apt-get autoremove -y &&\
  apt-get clean &&\
  rm -rf /usr/local/src/*