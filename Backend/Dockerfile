FROM node:18

# Set working directory
WORKDIR /app

# Copy and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app
COPY . .

# Expose backend port
EXPOSE 3005

# Start the backend server
CMD ["node", "server.js"]

