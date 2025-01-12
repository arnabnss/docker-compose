FROM node:19-alpine
RUN mkdir /app
COPY . /app
WORKDIR /app
RUN npm install
EXPOSE 5000
CMD node app.js
