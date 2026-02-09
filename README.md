# One Command Deploy — Docker + GitHub Actions CI/CD

This repository demonstrates how any application can be converted into a production-ready, automatically deployable system using Docker and GitHub Actions.

At DeployFast DevOps, we use this exact workflow to take a raw GitHub project and make it deployment-ready in minutes.

---

## Run the application locally (One Command)

docker-compose up --build

Open in browser:
http://localhost:8000

---

## What happens on every push to GitHub

Whenever code is pushed to the main branch:

1. GitHub Actions automatically starts
2. Docker image is built
3. Container is started and verified
4. Deployment is validated without manual steps

This is a real CI/CD pipeline, not just a Docker demo.

---

## Project Structure

Dockerfile  
docker-compose.yml  
.github/workflows/ci-cd.yml  
app/  

---

## Why this project matters

Most developers know Docker.  
Very few show automated CI/CD with it.

This project proves the ability to:

- Containerize applications
- Automate deployment using GitHub Actions
- Create one-command deployment systems
- Apply real DevOps practices to any repository

---

## About DeployFast DevOps

We help teams convert their projects into Dockerized, CI/CD-enabled, deployment-ready systems quickly and reliably.

Contact: deployfast.devops@gmail.com

