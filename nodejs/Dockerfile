FROM node:carbon

# create app dir
WORKDIR /usr/src/app

COPY ./conf/package*.json ./
RUN npm install

COPY ./conf/*.js ./

EXPOSE 8000

#
CMD ["npm", "start"]


