
# 🚀 End-to-End CI/CD Pipeline with Jenkins, Docker, SonarQube, and ArgoCD

This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline using **Jenkins**, **Docker**, **SonarQube**, **GitHub**, and **ArgoCD** for deploying containerized applications to a Kubernetes cluster.

---

## 🎯 Objective

To automate the process of:
- Pulling code from GitHub
- Building the application
- Running tests and SonarQube analysis
- Building and pushing Docker images
- Updating Kubernetes manifests
- Deploying to Kubernetes via ArgoCD

---

## 🛠️ Tools & Technologies

| Category         | Tools Used                             |
|------------------|-----------------------------------------|
| CI/CD            | Jenkins                                 |
| Source Control   | Git, GitHub                             |
| Build Tool       | Maven                                   |
| Code Analysis    | SonarQube                               |
| Containerization | Docker                                  |
| Registry         | DockerHub                               |
| Deployment       | Kubernetes,  ArgoCD                     |


---

##  CI/CD Pipeline Flow

Developer pushes code to GitHub
Jenkins triggers build
SonarQube performs static code analysis
Jenkins builds Docker image and pushes to registry
Jenkins updates Kubernetes manifests
ArgoCD auto-syncs and deploys the updated application

---
## Deploy Using ArgoCD
Install ArgoCD in Kubernetes
Add your Git repo to ArgoCD
Create an ArgoCD application

---
 ## Output
Jenkins job shows successful pipeline stages
Docker image pushed to DockerHub
ArgoCD shows deployment synced
Application running in Kubernetes:
kubectl get pods
