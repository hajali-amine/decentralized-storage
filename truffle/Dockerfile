FROM node:19-alpine3.15

WORKDIR /code

RUN npm install --location=global truffle

# TODO: rebuild image and use it with this env
ENV export NODE_OPTIONS=--openssl-legacy-provider

EXPOSE 8080