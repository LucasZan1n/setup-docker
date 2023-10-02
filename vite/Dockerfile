FROM node:lts

RUN npm install -g npm

RUN mkdir /srv/app

USER root

WORKDIR /srv/app

COPY /src /srv/app/

RUN npm i

CMD ["npm", "run", "dev"]

