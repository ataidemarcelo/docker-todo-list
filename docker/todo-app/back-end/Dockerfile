FROM node:14-alpine

WORKDIR /todo-app/backend/

ADD node_modules.tar.gz .

COPY . . 

EXPOSE 3001

CMD ["npm", "start"]