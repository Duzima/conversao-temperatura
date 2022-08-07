FROM node:10.19.0
WORKDIR ~/aula/app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]