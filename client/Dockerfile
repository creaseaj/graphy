FROM node:18

WORKDIR usr/src/app/client

COPY package*.json ./

RUN npm install

EXPOSE 3000

CMD ["yarn", "run", "dev"]
