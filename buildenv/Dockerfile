FROM ubuntu:latest
RUN apt-get update && apt-get install -y nasm xorriso grub-pc-bin make
COPY . /app
WORKDIR /app