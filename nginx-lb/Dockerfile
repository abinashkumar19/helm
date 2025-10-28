# Use official Nginx image
FROM nginx:latest

# Remove the default nginx index page
RUN rm -rf /usr/share/nginx/html/*

# Copy your custom HTML file into the default web root
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
