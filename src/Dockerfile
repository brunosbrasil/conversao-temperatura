ARG TAG=14.19.1
FROM node:$TAG
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . ./
CMD ["node", "server.js"]
EXPOSE 8080