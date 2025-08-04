# Task 1 - Automate Code Deployment Using CI/CD Pipeline

## Objective
Set up a CI/CD pipeline using GitHub Actions to build and deploy a Node.js app in a Docker container and push it to Docker Hub.

## Steps Followed
1. Forked the `nodejs-demo-app` repository.
2. Added a `Dockerfile` to containerize the application.
3. Created `.github/workflows/main.yml` for the GitHub Actions pipeline.
4. Configured secrets in GitHub:
   - `DOCKER_USERNAME` → My Docker Hub username
   - `DOCKER_PASSWORD` → My Docker Hub access token
5. Triggered the workflow by pushing changes to the `main` branch.
6. Verified the image was pushed to Docker Hub successfully.

## Proof of Completion
### Docker Hub Repository
![Docker Hub Screenshot](https://github.com/user-attachments/assets/5d55fe75-61df-4975-835f-e5cd471150cf)

### GitHub Actions Successful Run
![GitHub Actions Screenshot](https://github.com/user-attachments/assets/3f0ecf5f-6dcc-4a21-994f-2d7673f3dd72)

## Deliverables
- **GitHub Repo:** [https://github.com/ayishahiba/nodejs-demo-app](https://github.com/ayishahiba/nodejs-demo-app)
- **Docker Hub Repo:** [https://hub.docker.com/r/ayishahiba/nodejs-demo-app](https://hub.docker.com/r/ayishahiba/nodejs-demo-app)
