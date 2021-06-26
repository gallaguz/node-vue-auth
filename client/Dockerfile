FROM node:14.17.1-alpine3.13
WORKDIR /app
COPY package.json ./
RUN npm install
EXPOSE 8080
CMD ["npm", "run", "dev"]