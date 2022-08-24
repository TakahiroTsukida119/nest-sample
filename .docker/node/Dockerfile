FROM node:14.17.0

WORKDIR /app

RUN apt-get update && \
    apt-get install -y vim && \
    yarn install

EXPOSE 3000