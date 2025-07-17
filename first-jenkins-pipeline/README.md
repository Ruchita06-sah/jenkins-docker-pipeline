# Jenkins Pipeline with Docker Agent (Node.js)

This is a basic Jenkins Declarative Pipeline that demonstrates how to run a job inside a Docker container using the official `node:16-alpine` image.

## Tech Stack

- Jenkins
- Docker
- Node.js (`node:16-alpine` Docker image)

## What This Pipeline Does

This pipeline runs a single stage called `Test`, which simply prints the Node.js version inside a Docker container.
