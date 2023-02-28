FROM node:14.20-alpine3.16

WORKDIR /app
COPY build/ ./build/
COPY package.json package-lock.json .


RUN npm install serve
CMD npm run serve

EXPOSE 3000