ARG TAG=last
FROM node:$TAG
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . ./
CMD ["node", "server.js"]
EXPOSE 8080