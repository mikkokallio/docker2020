FROM node:current-slim
WORKDIR /usr/src/app
ENV API_URL=http://192.168.99.100:8000/
COPY package.json .
RUN npm i
EXPOSE 5000
CMD [ "npm", "start" ]
COPY . .