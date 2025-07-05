# Use official Nginx image
FROM nginx:alpine

# Remove default Nginx web content
RUN rm -rf /usr/share/nginx/html/*

# Copy our HTML file into Nginx public directory
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80
