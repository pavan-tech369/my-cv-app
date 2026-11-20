# My CV Website
Personal CV hosted as a Docker container on an AWS EC2 Ubuntu instance.

**Live URL:** http://65.0.7.230

## How It Works
1. Code is pushed to the `main` branch.
2. GitHub Actions builds the Docker image (Nginx serving `index.html`) and pushes it to Docker Hub (`pavangurjar/my-cv-app:latest`).
3. The container runs on an AWS EC2 `t3.micro` instance (Ubuntu 24.04) in the Mumbai region.

## Tools Used
* Nginx
* Docker & Docker Hub
* GitHub Actions
* AWS EC2
