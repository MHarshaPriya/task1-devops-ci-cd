FROM node:18-alpine
WORKDIR /app
COPY nodejs-demo-app/package*.json ./
RUN npm install
COPY nodejs-demo-app/ .
EXPOSE 3000
CMD ["node","index.js"]
