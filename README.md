# 🚀 CI/CD Pipeline Using GitHub Actions, Docker & AWS

**A DevOps project demonstrating automated application build, containerization, and deployment using GitHub Actions and AWS cloud services.**

## 📌 Project Overview

This project focuses on implementing a CI/CD pipeline to automate the build and deployment process of a Spring Boot application.

GitHub Actions is used to automate the pipeline, Docker is used for containerization, and AWS services provide the infrastructure for storing and deploying Docker images.

The main objective is to reduce manual deployment efforts and understand how different DevOps tools integrate to create an automated deployment workflow.

## 🏗️ Architecture

```text
Developer
    |
    v
GitHub Repository
    |
    v
GitHub Actions
    |
    v
Docker Image Build
    |
    v
Amazon ECR
    |
    v
Amazon EC2
    |
    v
Docker Compose
    |
    v
Running Application
```

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Git | Version Control |
| GitHub | Source Code Management |
| GitHub Actions | CI/CD Automation |
| Docker | Containerization |
| Docker Compose | Container Management |
| AWS EC2 | Cloud Infrastructure |
| AWS ECR | Container Image Registry |
| AWS IAM | Identity and Access Management |
| Java | Programming Language |
| Spring Boot | Backend Framework |
| Maven | Build Automation |

## ⚙️ CI/CD Workflow

1. **Code Management:** Source code is maintained in a GitHub repository.
2. **Pipeline Trigger:** GitHub Actions triggers the workflow when code changes are pushed.
3. **Build Process:** Maven builds the Spring Boot application.
4. **Dockerization:** Docker packages the application into a container image.
5. **Image Management:** The Docker image is pushed to Amazon ECR.
6. **Cloud Deployment:** Amazon EC2 hosts the application.
7. **Container Execution:** Docker Compose manages application containers on the EC2 instance.

## 📂 Project Structure

```text
CI-CD-Pipeline/
│
├── .github/
│   └── workflows/
│
├── .mvn/
│
├── src/
│
├── target/
│
├── Dockerfile
├── docker-compose.yml
├── pom.xml
├── mvnw
├── mvnw.cmd
├── README.md
└── .gitignore
```

## ☁️ AWS Services

### Amazon EC2
Provides virtual server infrastructure to host and run the application.

### Amazon ECR
Stores and manages Docker container images.

### AWS IAM
Manages access permissions between GitHub Actions and AWS services.

## 🎯 Key Learning Outcomes

- Understanding CI/CD pipeline architecture.
- Automating builds using GitHub Actions.
- Containerizing Java applications using Docker.
- Managing container images using Amazon ECR.
- Deploying applications on AWS EC2.
- Understanding AWS IAM permissions.
- Working with Docker Compose.
- Integrating GitHub with AWS services.

## 👩‍💻 Author

**Khushi Tyagi**

M.Tech CSE | DevOps & Cloud Computing Enthusiast

GitHub: Khushi Tyagi

---

⭐ Exploring DevOps | AWS | Docker | CI/CD | Cloud Infrastructure