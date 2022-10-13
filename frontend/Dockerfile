FROM node:12.18.1

RUN mkdir -p /app

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]


RUN npm install 


ADD src /app/src
ADD public /app/public


EXPOSE 3000


CMD [ "npm", "start" ]
