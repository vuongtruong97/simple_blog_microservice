FROM node:17.0.0-alpine

WORKDIR /usr/app

COPY ./package.json ./

RUN npm install 

COPY ./ ./

CMD ["npm","start"]
