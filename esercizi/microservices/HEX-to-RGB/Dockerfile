FROM node:alpine
COPY . .
WORKDIR /microservices
COPY ./commons/src/model/Color.ts /HEX-to-RGB
WORKDIR /microservices/HEX-to-RGB
RUN npm install
EXPOSE 3000
CMD npm start