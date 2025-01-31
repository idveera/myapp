# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy your HTML files to the Nginx default directory
COPY . /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
