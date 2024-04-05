# Set base image
FROM node:latest

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy src directory
COPY src ./src

# Expose port
EXPOSE 5000

# Command to run the application
CMD ["node", "src/server.js"]
