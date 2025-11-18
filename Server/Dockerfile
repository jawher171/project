
FROM node:lts-alpine

WORKDIR /ReactApp

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 9000

CMD ["npm", "start"]
