FROM node:latest
WORKDIR /usr/src/app
COPY ./src/app.js .
COPY package.json .
RUN npm install express --save
EXPOSE 9000
CMD ["npm","start"]
