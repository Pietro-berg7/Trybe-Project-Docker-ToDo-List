FROM node:14

WORKDIR /
ADD ./node_modules.tar.gz  .

COPY . .

EXPOSE 3001

CMD [ "npm", "start"]