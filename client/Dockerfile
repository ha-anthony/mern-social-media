# Base image
FROM node:10

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY ./package*.json ./

# Update npm and install dependencies
RUN npm install
#RUN npm install --legacy-peer-deps

#ENV NODE_OPTIONS="--openssl-legacy-provider"

# Copy application code
COPY . .

# Expose port and start application
EXPOSE 3000
CMD ["npm", "start"]
