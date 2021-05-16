FROM node:15-alpine

WORKDIR /app

COPY . .

RUN yarn install

RUN npx hardhat compile
