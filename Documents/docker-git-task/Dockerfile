FROM node:20-alpine

WORKDIR /app

# Initialize package.json and install Express inside the container
RUN npm init -y && npm install express

# Copy your application files
COPY Documents/docker-git-task/server.js Documents/docker-git-task/index.html ./

EXPOSE 3000

CMD ["node", "server.js"]
