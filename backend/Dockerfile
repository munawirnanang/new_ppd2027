FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
# Gunakan nodemon di dev agar auto-restart
RUN npm install && npm install -g nodemon
COPY . .
EXPOSE 5000
CMD ["nodemon", "index.js"]