# Specify a base image
FROM node:14-alpine

# Install some depenendencies inside of the Alpine Image
COPY ./ ./
RUN npm install


# Default command
CMD ["npm", "start"]