FROM node:20

WORKDIR /microProductos
COPY package.json .
RUN npm install

EXPOSE 3002

COPY . .
CMD npm start