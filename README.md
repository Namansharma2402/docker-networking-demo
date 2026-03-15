# Dockerized Networking Demo

This project demonstrates a simple containerized web application deployed using Docker.

## Features
- Python Flask web service
- Docker containerization
- Port exposure for network access
- Health endpoint for monitoring

## Run locally

Build the image:

docker build -t devops-network-demo .

Run the container:

docker run -d -p 5000:5000 devops-network-demo

Open in browser:

http://localhost:5000

## Cloud Deployment

The container can be deployed on AWS EC2 and accessed through the public IP by exposing port 5000 in the security group.