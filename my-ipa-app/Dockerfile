# Use the official Nginx image as a base image
FROM nginx:latest

# Copy the application files to the Nginx directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]