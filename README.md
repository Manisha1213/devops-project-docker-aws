#  DevOps Project - CI/CD Pipeline
##  Overview
This project demonstrates a complete DevOps workflow:
- Dockerized Python application
- CI/CD pipeline using Jenkins
- Deployment on AWS EC2
##  Tech Stack
- Python
- Docker
- Jenkins
- AWS EC2
##  Architecture
App → Docker → EC2
##  Live Demo
http://<your-public-ip>:5000
##  Steps to Run
docker build -t myapp .
docker run -p 5000:5000 myapp
