FROM node:20
WORKDIR /user/src/app

COPY app.js .
COPY package.json .
COPY views / ./views

RUN npm install

ENTRYPOINT ["node", "./app.js"]