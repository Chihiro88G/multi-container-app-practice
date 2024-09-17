FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME name
ENV MONGODB_PASSWORD password

CMD [ "node", "app.js" ]