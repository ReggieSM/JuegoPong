FROM node
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json /usr/src/app
RUN npm install
RUN npm i -s nodemon
COPY . /usr/src/app
EXPOSE 8080
ENV PORT=8080
CMD [ "npm", "start"]
