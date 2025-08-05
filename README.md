# Jenkins Pipelines with Docker Agents

This project demonstrates two Jenkins Declarative Pipelines designed to showcase container-based builds using Docker agents. 
The goal is to understand how Jenkins can dynamically spin up Docker containers to perform isolated and repeatable CI tasks.

## Project Overview

Pipeline 1: Basic Docker Agent Pipeline
A simple pipeline that uses a Node.js Docker image to execute a basic test step. 

Pipeline 2: Multi-Agent, Multi-Stage Pipeline
A more advanced pipeline that runs separate stages for frontend and backend in different Docker containers:
- **Backend**: Simulated using a Python container.
- **Frontend**: Simulated using an NGINX container.

## Tools & Technologies
- Jenkins
- Docker
- Node.js
- Python
- NGINX

## Purpose
This project is part of a hands-on DevOps learning journey focused on mastering CI/CD pipelines with Jenkins and Docker.
It lays the groundwork for more complex workflows involving testing, building, and deploying modern applications.

