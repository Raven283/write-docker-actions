FROM node:slim

COPY package* ./

RUN npm install

COPY . .

CMD [ "node", "/src/index.js" ]