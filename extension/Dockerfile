FROM node:18-alpine3.18
LABEL maintainer="Professional Services <ps-dev@commercetools.com>"

WORKDIR /app

COPY . /app

RUN npm ci --only=prod
CMD [ "node", "src/init.js" ]
