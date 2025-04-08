# CI/CD DevOps Pipeline (Jenkins + Docker + Kubernetes)

## 📌 Project Description
An end-to-end DevOps pipeline for microservices deployment. Automates build, test, analysis, artifact storage, and deployment to Kubernetes.

## 🧰 Stack
- Jenkins
- SonarQube
- Nexus Repository
- Docker
- Kubernetes
- GitHub
- Maven

## 🔄 Pipeline Breakdown
- Code checkout → Build with Maven
- Static code analysis with SonarQube
- Artifact stored in Nexus
- Docker image build & push
- Deployment to Kubernetes

## 🛠️ Instructions
1. Configure Jenkins pipeline with webhook triggers
2. Use SonarQube & Nexus integrations
3. Set up Kubernetes deployment YAML files

## 📈 Benefits
- Automated, fast deployments
- Code quality gates
- Version-controlled artifacts
