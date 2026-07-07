FROM node:20-alpine

WORKDIR /app

COPY package*.json .

RUN npm install --allow-scripts

COPY . /app

EXPOSE 5173

CMD ["npm", "run", "dev"]
