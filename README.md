# CI/CD with Docker and GitHub Actions

This project demonstrates a simple CI/CD pipeline using Docker and GitHub Actions.

## Technologies

* Node.js
* Docker
* GitHub Actions

## Workflow

1. Code is pushed to GitHub
2. GitHub Actions triggers the pipeline
3. Docker image is built
4. Docker container runs automatically

## Run Locally

Build image

docker build -t ci-cd-docker-project .

Run container

docker run -p 3000:3000 ci-cd-docker-project
