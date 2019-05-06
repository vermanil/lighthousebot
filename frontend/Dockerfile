FROM node:8
WORKDIR /lighthouse_bot
COPY package*.json /lighthouse_bot/
RUN npm install
COPY . /lighthouse_bot
EXPOSE 8000
CMD ["npm", "start"]
