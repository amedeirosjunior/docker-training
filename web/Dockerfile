FROM node:latest

WORKDIR /web

COPY package.json ./

RUN npm install
RUN npm install -g @angular/cli -v latest

COPY . .

EXPOSE 4200

CMD ["npm", "start"]