FROM node:16

WORKDIR /app-frontend

COPY package.json /app-frontend

RUN npm install

COPY . /app-frontend

RUN npm run build

EXPOSE 3001

CMD ["npm","start"]