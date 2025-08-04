# Task 1 - DevOps Internship Project 🚀

This is a Node.js-based demo project for DevOps CI/CD pipeline implementation using GitHub Actions and Docker.

## ✅ Features

- Simple Node.js application
- GitHub Actions for CI/CD
- Dockerized setup
- Automatic Docker image push to DockerHub on every push to `main` branch

## 🛠️ Tech Stack

- Node.js
- GitHub Actions
- Docker
- DockerHub


## Steps
2. Create a new file in the `.github/workflows/main.yml` directory
3. Define the workflow
4. Push the changes to the repository
5. Check the Actions tab in the repository

🔁 GitHub Actions Workflow

Installs dependencies
Runs test script
Builds Docker image
Pushes to DockerHub using GitHub Secrets:
- DOCKER_USERNAME
- DOCKER_PASSWORD
