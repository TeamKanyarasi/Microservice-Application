FROM node:18
WORKDIR /app
COPY . .
RUN npm install
RUN npm install express
EXPOSE 3003
CMD [ "node", "index.js" ]