FROM node:alpine

WORKDIR /app

COPY package.json ./

RUN yarn install

COPY ./ ./

CMD ["yarn", "dev", "--host", "0.0.0.0"]