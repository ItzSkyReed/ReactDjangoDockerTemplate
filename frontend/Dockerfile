FROM node:22-alpine3.19

WORKDIR /app/frontend/

COPY package*.json /app/frontend/

COPY . /app/frontend/
RUN npm install

CMD ["npm", "start"]