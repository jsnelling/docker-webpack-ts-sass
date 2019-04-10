FROM node:8.15.1-alpine

WORKDIR /app

COPY package*.json ./

COPY . /app

RUN \
  apk update                     && \
  apk add bash                   && \
  npm install -G yarn typescript && \
  yarn 

EXPOSE 8080