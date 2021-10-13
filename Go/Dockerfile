FROM golang:1.17.2-buster

WORKDIR /app

COPY ./app /app

RUN apt update \
  && apt upgrade -y

ENV PATH $PATH:/usr/local/go/bin