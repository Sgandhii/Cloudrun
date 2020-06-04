FROM node:12.6.0-alpine
WORKDIR /app
COPY /dist ingestion/downtime-alert-service/app/dist/
COPY node_modules/ app/node_modules/
EXPOSE 8080
CMD node /app/dist/main.js
