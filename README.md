# MEAN Stack DevOps Assignment

## Live App
http://<YOUR_VM_PUBLIC_IP>

## GitHub Repo
https://github.com/soniyada/crud-mean-devops

## Docker Hub Images
https://hub.docker.com/r/soni841/frontend  
https://hub.docker.com/r/soni841/backend  

## Tech Stack
- Angular (Frontend)
- Node.js + Express (Backend)
- MongoDB
- Docker & Docker Compose
- Nginx Reverse Proxy
- GitHub Actions CI/CD

## CI/CD
On every push to the main branch:
- Docker images are built
- Pushed to Docker Hub
- Deployed automatically to cloud VM

## Run Locally
docker-compose up -d
