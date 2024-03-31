# Use the official lightweight Node.js 14 image
FROM node:20-alpine

# Set the working directory inside the container
WORKDIR /app
# Copy package.json and package-lock.json
COPY package*.json .

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Build the React app


# Expose port 3000 to the outside world
EXPOSE 3000

# Run the React app
CMD ["npm", "start","dev"]
