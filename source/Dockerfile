FROM node:6.7.0
MAINTAINER Hoang Nam "particle4dev@gmail.com"

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install app dependencies
RUN npm install -g create-react-app

# Bundle app source
# COPY . /usr/src/app

EXPOSE 3000 9000
CMD tail -f /dev/null
