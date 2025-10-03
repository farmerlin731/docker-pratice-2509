FROM node:14

WORKDIR /app

COPY package.json .

RUN npm insall

COPY . .

EXPOSE 80

CMD [ "node","server.js" ]