FROM node:lts-slim as dev

WORKDIR /app

COPY . .
EXPOSE 8080

RUN npm install

ENTRYPOINT [ "npm", "run", "dev" ]