FROM node:14.4.0-alpine
WORKDIR /app
COPY package.json .
RUN npm i
COPY . .
CMD ["npm", "start"]