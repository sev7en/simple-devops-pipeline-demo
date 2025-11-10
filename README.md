# Simple DevOps Pipeline Demo

A minimal CI/CD demo using **GitHub Actions** and **Docker**.

### Features:
- Python Flask app
- Docker container build
- Automated pipeline: build → test → deploy (mock)
- Runs on every push or pull request

### How to run locally:
```bash
docker build -t simple-devops-demo .
docker run -p 5000:5000 simple-devops-demo
