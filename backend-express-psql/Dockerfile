FROM node:lts-alpine3.17

WORKDIR /example-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
