FROM ubuntu
RUN apt-get update && apt-get install nodejs -y && apt-get install nodejs-legacy -y && apt-get install npm -y
RUN echo "Git Clone Repository"
COPY . /tmp/
WORKDIR /tmp/node-js-sample/
RUN echo pwd
RUN npm install
EXPOSE 5000
CMD [ "npm", "start" ]

