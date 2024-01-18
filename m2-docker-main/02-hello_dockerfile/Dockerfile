FROM node:21-alpine3.18
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3333
CMD ["node", "./server.js"]