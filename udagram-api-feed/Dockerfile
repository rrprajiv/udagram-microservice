FROM node:12
# create app directory
WORKDIR /usr/src/app
# install app dependencies
COPY package*.json ./

RUN npm ci
# bundle app source
COPY . .

EXPOSE 8080

CMD ["npm", "run", "prod"]
