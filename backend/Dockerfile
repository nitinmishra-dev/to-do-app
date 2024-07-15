FROM node:14-alpine3.12
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 4000
CMD ["node", "backend/index.js"]
