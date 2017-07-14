FROM alpine:latest

MAINTAINER Kevin Bradwick <kevinbradwick@gmail.com>

RUN apk add --update yarn

RUN mkdir /workspace

WORKDIR /workspace

VOLUME /workspace

ENTRYPOINT ["yarn"]