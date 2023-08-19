
# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy your dynamic web page files to the appropriate directory in the image
COPY . /usr/share/nginx/html

# Expose port 80 for HTTP traffic
EXPOSE 80

# Command to start the Nginx server when the container runs
CMD ["nginx", "-g", "daemon off;"]


# docker Command


# docker build -t html . 

# docker run -p 8080:8080 -d html .

# http://localhost:8080/index.html