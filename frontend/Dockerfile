FROM nginx
# Set the PORT environment variable
ENV PORT 80

# Expose the port (optional but good practice)
EXPOSE 80
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/index.html