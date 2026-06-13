# Docker ECS Flask Project

## Overview

This project demonstrates containerizing a Flask application using Docker and deploying it to AWS ECS Fargate.

## Technologies Used

* Python Flask
* Docker
* Amazon ECR
* Amazon ECS Fargate
* AWS CloudShell

## Application

The Flask application returns:

Hello from ECS Fargate!

## Files

* app.py
* Dockerfile
* requirements.txt

## Docker Commands

docker build -t flask-demo .

docker run -d --name flask-container -p 5000:5000 flask-demo

## AWS Deployment Steps

1. Build Docker image
2. Push image to Amazon ECR
3. Create ECS Task Definition
4. Create ECS Service
5. Deploy on AWS Fargate
6. Access application through public IP

## Output

Hello from ECS Fargate!
