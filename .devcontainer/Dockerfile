FROM docker.io/ubuntu:22.04

RUN apt update -y && apt upgrade -y
RUN DEBIAN_FRONTEND=noninteractive apt install -y lxde
RUN apt install -y tigervnc-standalone-server tigervnc-common
RUN apt install -y novnc websockify
