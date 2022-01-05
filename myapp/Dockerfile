FROM node:12.18.1
ENV NODE_ENV=production
WORKDIR /app
COPY [ ".", "/app" ]
RUN npm install --production
CMD [ "node", "index.js" ]


