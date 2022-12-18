FROM node:14.15.4
LABEL maintainer="danielrosas76@gmail.com"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["npm", "start"]