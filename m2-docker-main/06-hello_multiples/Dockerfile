FROM node:12.17-alpine3.19
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 5432
CMD ["node", "./server.js"]