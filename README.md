# CI/CD Pipeline with Kubernetes, Docker & Jenkins

A complete DevOps project showcasing the implementation of a CI/CD pipeline using *Jenkins, **Docker, and **Kubernetes* for seamless deployment of a Python application.

## Project Structure


DevOps-Project-01/
│
├── Jenkins/
│   └── Jenkinsfile
│
├── Kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
│
├── Dockerfile
├── app.py
├── requirements.txt
└── README.md


## Tech Stack

- *Jenkins* – Automation server for building pipelines  
- *Docker* – Containerization of application  
- *Kubernetes* – Container orchestration  
- *Python* – Sample application  
- *GitHub* – Source code management

## Pipeline Overview

1. *Code Push* – Code is pushed to GitHub  
2. *Build Triggered* – Jenkins triggers the build  
3. *Docker Image* – Jenkins builds a Docker image and pushes it to Docker Hub  
4. *Kubernetes Deployment* – Jenkins deploys the latest image to a Kubernetes cluster

## Prerequisites

- Docker & Docker Hub account  
- Kubernetes cluster (e.g., Minikube, EKS)  
- Jenkins configured with Docker and Kubernetes plugins  
- GitHub repository

## Setup Instructions

1. *Clone Repository*

   bash
   git clone https://github.com/IamAsifOps/ci-cd-pipeline-k8s-docker-jenkins.git
   cd ci-cd-pipeline-k8s-docker-jenkins
   

2. *Jenkins Pipeline*

   - Import Jenkins/Jenkinsfile into your Jenkins pipeline  
   - Configure Docker credentials and Kubernetes context  

3. *Build and Deploy*

   - Push changes to GitHub  
   - Jenkins will:  
     - Build and push Docker image  
     - Apply Kubernetes deployment.yaml and service.yaml

## Screenshots

Coming soon...

---

## Connect with Me

- *GitHub*: [IamAsifOps](https://github.com/IamAsifOps)  
- *LinkedIn*: [Asif Ahamed](https://www.linkedin.com/in/asif-ahamed-devops/)

---

> If you found this useful, feel free to star the repository and connect!
