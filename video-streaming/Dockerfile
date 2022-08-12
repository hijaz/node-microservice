FROM node:12.18.1-alpine

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --only=production
COPY ./videos ./videos
COPY ./index.js ./index.js
ENV PORT=3000
CMD npm start