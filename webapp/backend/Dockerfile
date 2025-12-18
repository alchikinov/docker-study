FROM node:22-alpine

WORKDIR /backend-app
COPY package.json ./
COPY index.js ./
COPY .env ./

RUN npm install
RUN apk add curl


EXPOSE 5050

# option to start (launch commang)
#CMD [ "start", "npm" ]

# other option to start
CMD [ "start" ]
ENTRYPOINT [ "npm" ]