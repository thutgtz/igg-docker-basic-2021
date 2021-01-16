FROM node:14-alpine3.12
COPY package.json server.js package-lock.json ./
RUN npm install 
CMD ["npm", "start"]
