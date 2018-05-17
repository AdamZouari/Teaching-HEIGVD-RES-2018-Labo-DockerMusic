FROM node:latest

MAINTAINER Adam Zouari <adam.zouari@heig-vd.ch>

COPY src /opt/res/

WORKDIR /opt/res/

RUN npm install

ENTRYPOINT ["node", "/opt/res/musician.js"]
