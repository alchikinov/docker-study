FROM node:22-alpine

WORKDIR /backend-app
COPY package.json ./
COPY index.js ./
COPY .env ./

RUN npm install

EXPOSE 5050

#CMD [ "start", "npm" ]

CMD [ "start" ]
ENTRYPOINT [ "npm" ]