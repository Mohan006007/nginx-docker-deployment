# Nginx Docker Deployment

This project demonstrates how to deploy an Nginx web server inside a Docker container, using a custom `Dockerfile` and `docker-compose.yml`. It also showcases the usage of bind mounts to share files between the host and the container.

## Project Structure

- **Dockerfile**: Defines the Nginx container image setup.
- **docker-compose.yml**: Automates container setup and configuration, binding port 80.
- **index.html**: A simple HTML file served by Nginx.
- **script.sh**: A script for any required automation.
- **nginx-bind-mount.png**: Screenshot showing successful bind mount setup.
- **ec2-server.png**: EC2 instance running screenshot.
- **output-via-browser.png**: Screenshot of browser output.

## Features

- Dockerized Nginx web server
- Bind mount for sharing content between host and container
- Easy deployment using Docker Compose

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohan006007/nginx-docker-deployment.git
   cd nginx-docker-deployment
2. Build and run the containers with Docker Compose:
   ```bash
   docker-compose up -d
3. Access the Nginx server at http://localhost or the IP of your EC2 instance if deployed on AWS.
