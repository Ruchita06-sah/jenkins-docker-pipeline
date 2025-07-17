# Jenkins Multi-Stage Pipeline with Docker Agents (Python & NGINX)

This project showcases a Jenkins Declarative Pipeline with multiple stages, each running inside a different Docker container. It simulates a Python-based backend and an NGINX-based frontend environment.

## What This Pipeline Does

- Stage 1 – Back-end (Python)
  - Uses Docker image: `python:3.11-slim`
  - Prints Python and pip versions
  - Simulates a backend setup (e.g., Flask, FastAPI)

- Stage 2 – Front-end (NGINX)
  - Uses Docker image: `nginx:alpine`
  - Prints the NGINX version
  - Simulates serving a static site
