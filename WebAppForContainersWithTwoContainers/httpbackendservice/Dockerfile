# FROM node:current-alpine
FROM node:24.1.0-alpine3.20
COPY . /app
WORKDIR /app
RUN npm install
EXPOSE 5000
CMD [ "node", "app.js" ]