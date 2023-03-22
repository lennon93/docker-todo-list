FROM node.14

WORKDIR /app

ADD node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]