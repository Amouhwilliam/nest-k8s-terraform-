FROM node:20.11.1

WORKDIR /app
COPY package*.json .

RUN yarn install
COPY . .
RUN yarn build


CMD ["yarn", "start"]

EXPOSE 3000