
FROM ubuntu:18.04

RUN apt-get update && apt-get -y install curl gnupg && curl -sL https://deb.nodesource.com/setup_13.x  | bash - && apt-get -y install nodejs


WORKDIR /app/frontend
COPY . /app/frontend

<<<<<<< HEAD
RUN npm install 
=======
RUN npm install

>>>>>>> e46818021bbad94ee9c5a80b2d31d6fe39f67f0e

VOLUME /app/frontend

CMD npm start
