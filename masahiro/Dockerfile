FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

# vimとgitインストール
RUN apt update -y && apt install git -y && apt-get install vim -y

# FlutterをGithubからclone
RUN git clone https://github.com/flutter/flutter.git

# Flutterを使うのに必要なパッケージをインストール
RUN apt-get install unzip clang xserver-xorg pkg-config libgtk-3-dev curl cmake ninja-build -y
