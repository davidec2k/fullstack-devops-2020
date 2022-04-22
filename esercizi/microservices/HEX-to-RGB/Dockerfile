FROM node:alpine
COPY package.json /API
WORKDIR /API
RUN npm install
WORKDIR /API/dist/HEX-to-RGB/src/
EXPOSE 3000
CMD ["node","HttpServer.js"]