FROM node:14.14.0-alpine

WORKDIR '/app'

COPY ./package.json ./

RUN npm run install

COPY ./ ./

CMD ["npm", "run", "start"]
