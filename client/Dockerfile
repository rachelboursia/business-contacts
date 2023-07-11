FROM node

WORKDIR /app

COPY . .app

RUN npm install && npm run build

EXPOSE 1234

CMD ["node", "server.js"]