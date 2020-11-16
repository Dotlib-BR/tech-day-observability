FROM node:14.5

WORKDIR /usr/src/app

COPY ./web .

RUN npm install

EXPOSE 3000

ENTRYPOINT ["npm", "start"]