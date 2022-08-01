FROM node:lts-alpine

RUN apk add yarn

WORKDIR /var/www/html/app

ENV PATH /var/www/html/app/node_modules/.bin:$PATH

COPY package*.json .

RUN yarn install

CMD ["yarn", "dev"]