FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app-todo/tests

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "test"]