# Base image
FROM node 

# Set defaukt working directory
WORKDIR /app

# Copy requirement files to working directory
COPY package.json /app

# Run necessary command to install required package
RUN npm install

# Copy application files to working directory
COPY . /app

# Run application at designated port
EXPOSE 80

# Executing application after image is build
CMD [ "node", "server.js" ]