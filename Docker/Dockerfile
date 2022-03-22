FROM node:17

WORKDIR /shop

COPY shop/package.json ./

RUN yarn

COPY shop/. .

CMD ["yarn","start"]