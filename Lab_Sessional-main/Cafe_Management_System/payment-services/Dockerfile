FROM node:23-alpine

WORKDIR /app

COPY package*.json ./
COPY package-lock.json ./

RUN npm install

COPY . .

EXPOSE 3003

CMD ["node", "index.js"]