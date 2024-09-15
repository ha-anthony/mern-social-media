# Use the official Nginx image as a base
FROM nginx:latest

# Copy the custom nginx.conf file to the container
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy the SSL certificate and key to the container
COPY nginx.crt /etc/nginx/ssl/nginx.crt
COPY nginx.key /etc/nginx/ssl/nginx.key
