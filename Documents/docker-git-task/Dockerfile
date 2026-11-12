FROM node:20-alpine
RUN apk add --no-cache git
WORKDIR /repo
RUN git clone -b master https://github.com/ayushpkl/docker_task.git .
WORKDIR /repo/Documents/docker-task
RUN npm install
EXPOSE 3000
CMD ["node", "server.js"]
