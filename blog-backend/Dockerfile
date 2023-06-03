FROM node:16

WORKDIR /app-backend

ENV NODE_ENV=production

COPY package.json /app-backend

RUN npm install

COPY . /app-backend

EXPOSE 3001

CMD ["npm","start"]