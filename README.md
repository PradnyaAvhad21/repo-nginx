# repo-nginx
# Overview
This Docker project provides a lightweight Nginx server configured with a custom Nginx configuration file. The Docker image is based on the official Nginx image and includes a modified Nginx configuration to serve static content.

# Features
Based on the latest Nginx image.

Custom Nginx configuration file included.

Exposes port 80 for HTTP traffic.

Easy to use and deploy with Docker.

# Usage
following are the steps:

Pull the Docker Image:

# docker pull avhadpradnya21/docker-nginx:latest

Run a Docker Container:

# docker run -d -p 8080:80 avhadpradnya21/docker-nginx:latest

This command will start the Nginx server in a Docker container, and can access it by navigating to http://localhost:8080⁠ in web browser.
