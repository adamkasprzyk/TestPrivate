ARG NODE_VERSION=14.20-alpine3.16
FROM node:${NODE_VERSION}

WORKDIR /app
COPY build/ ./build/
COPY package.json package-lock.json .

RUN npm install serve
CMD npm run start:prod

USER 1000
EXPOSE 3000