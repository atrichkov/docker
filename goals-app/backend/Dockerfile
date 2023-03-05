FROM node:16

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGO_USER=root

ENV MONGO_PASSWORD=root

ENV PORT=80

EXPOSE $PORT

CMD [ "npm", "start" ]