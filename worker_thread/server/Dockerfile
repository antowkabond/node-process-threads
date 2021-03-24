FROM node:14.16.0-alpine3.10
WORKDIR /usr/src/app
COPY *.js ./
COPY package*.json ./
RUN npm install
EXPOSE 8000
CMD [ "node", "server.js" ]
