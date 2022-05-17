FROM node

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

ARG PORT=80

EXPOSE $PORT

CMD ["node", "app.js"]