FROM node:18-alpine

WORKDIR /app 

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 7002

CMD ["npm", "run", "dev"]