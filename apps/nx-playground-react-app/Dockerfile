# Use a Node.js base image
FROM node:21-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the built files from the Nx dist folder into the container
COPY dist/apps/nx-playground-react-app /app

# Expose the port your app will run on
EXPOSE 3000

# Run the app
CMD ["npx", "serve", "/app", "-s", "-l", "3000"]
