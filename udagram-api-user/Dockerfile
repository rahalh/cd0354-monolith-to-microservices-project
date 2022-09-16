FROM node:12

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm i
# Regroupement des sources de l'application
COPY . .
EXPOSE 8080
CMD [ "npm", "run", "prod" ]