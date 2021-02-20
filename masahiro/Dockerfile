FROM ubuntu:20.04

# RUN apt-get update && apt-get install git unzip clang xserver-xorg pkg-config libgtk-3-dev curl cmake ninja-build
RUN apt update -y && apt install git -y && apt-get install vim -y
ENV DEBIAN_FRONTEND=noninteractive
RUN git clone https://github.com/flutter/flutter.git
RUN apt-get install unzip clang xserver-xorg pkg-config libgtk-3-dev curl cmake ninja-build -y
# RUN export PATH="$PATH:/flutter/bin" >> ~/.bashrc
# RUN [ "flutter", "--version" ]
