FROM node:18

WORKDIR /usr/src/virtual-classroom/assignment_service

COPY package*.json ./

COPY . .

RUN npm install

EXPOSE 3003

CMD ["node", "server.js"]
