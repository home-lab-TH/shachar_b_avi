FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
# We use 5000 as defined in your README
EXPOSE 5000
CMD ["node", "server.js"]