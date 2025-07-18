# Use Node LTS as base
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy and install dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

# Expose port and start the server
EXPOSE 5000
CMD ["npm", "start"]
