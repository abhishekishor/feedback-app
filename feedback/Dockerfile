FROM node:14

WORKDIR /app

COPY package.json .

npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]