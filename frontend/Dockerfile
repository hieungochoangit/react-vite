FROM node:lts-alpine3.17

WORKDIR /var/www/frontend

COPY package*.json .

RUN yarn install

COPY . .

EXPOSE 5173

CMD ["yarn", "dev"]
