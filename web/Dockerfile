FROM node:8.15.1-alpine

ADD . /app
WORKDIR /app

EXPOSE 8080

RUN \
  apk update                     && \
  apk add bash                   && \
  npm install -G yarn typescript && \
  yarn 