FROM node:16

# Set the working directory correctly
WORKDIR /app

# Copy dependencies first
COPY package.json package-lock.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Ensure correct start command
CMD ["npm", "start"]