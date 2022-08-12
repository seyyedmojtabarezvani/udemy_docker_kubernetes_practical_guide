FROM node:18-alpine3.15

WORKDIR /app

COPY ./first-demo-starting-setup/package.json .

RUN npm install

COPY ./first-demo-starting-setup/* .

EXPOSE 3000

CMD [ "node", "app.mjs" ]