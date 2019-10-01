FROM node:12.2.0-alpine

# Prepare app directory
WORKDIR /usr/src/app/
COPY package*.json ./

# Copy source code
COPY . .

RUN yarn install

# Start service
CMD [ "yarn", "start" ]
