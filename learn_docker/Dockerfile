FROM node:21-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000

CMD [ "npm", "start" ]

# docker tag <image-name> username/image-name
# docker push username/image-name