FROM node:20-alpine

WORKDIR /app

# Copy the app files directly from the build context
COPY Documents/docker-task/server.js Documents/docker-task/index.html ./

EXPOSE 3000

CMD ["node", "server.js"]
