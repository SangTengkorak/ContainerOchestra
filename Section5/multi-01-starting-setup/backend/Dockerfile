FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=matjangkrik
ENV MONGODB_PASSWORD=pow3ranger

CMD ["npm", "start"]