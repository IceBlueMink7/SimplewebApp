# Specify a base image
FROM node:14-alpine

WORKDIR /usr/app

# Install some depenendencies inside of the Alpine Image
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]