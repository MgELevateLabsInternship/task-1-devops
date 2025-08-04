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

After Successfully running Workflow. we will get this

<img width="1920" height="804" alt="Update readme md · MgELevateLabsInternship_task-1-devops@8fb54f0 - Brave 04-08-2025 21_22_18" src="https://github.com/user-attachments/assets/81b90146-520c-48ce-b641-45756b65d758" />

We will get docker nodejs image in our DockerHub Repo like this

<img width="1920" height="815" alt="Restrictions 04-08-2025 21_28_42" src="https://github.com/user-attachments/assets/07ade014-e894-4498-8f6a-c8bdc030ba79" />
