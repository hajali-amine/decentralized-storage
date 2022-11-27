FROM node:19-alpine3.15

WORKDIR /app

RUN npm install -g ganache-cli

ENV NODE_OPTIONS=--openssl-legacy-provider

EXPOSE 8545

CMD ["ganache-cli", "-h", "0.0.0.0"]