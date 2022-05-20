FROM node:alpine

WORKDIR /web

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4200

CMD npm start