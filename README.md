![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20App-lightgrey)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![GitHub Actions](https://img.shields.io/badge/CI-CD-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

A lightweight Flask application demonstrating CI/CD automation using GitHub Actions and Docker.

---

## 📌 Project Overview

This project demonstrates:

- How to build a lightweight Flask application  
- How to containerize it using Docker  
- How to automate testing and builds using GitHub Actions  
- How CI/CD pipelines work in real-world DevOps workflows  

---

## 🚀 Features

- Simple Flask web application
- Dockerized for portability
- Automated CI pipeline using GitHub Actions
- Unit tests included
- Ready for deployment to AWS, Azure, or GCP
- Clean and minimal codebase for demonstration

---

## 🧱 Tech Stack

- Python 3
- Flask 3.1.2
- Docker

---

## 🛠️ Getting Started

### Prerequisites
- Python 3.9+
- Docker (for containerization)

---

### 1. Run Locally (without Docker)

```bash
# Clone the repo
git clone git@github.com:Kalkireddy/flask-cicd-app.git
cd flask-cicd-app/app

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

---

### 2. Run with Docker

Build the image:
```bash
docker build -t flask-app .
```

Run the container:
```bash
docker run -p 5000:5000 flask-app
```

App will be available at: http://localhost:5000

---

### 3. Repo Structure

```
flask-cicd-app/
├── app.py
├── Dockerfile
├── requirements.txt
├── tests/
│   └── test_app.py
├── .github/
│   └── workflows/
│       └── ci.yml
└── README.md
```

---

## 🏗️ CI/CD Pipeline Overview

Developer Push → GitHub Actions → Install Dependencies → Run Tests → Build Docker Image → (Optional) Deploy

The pipeline includes:
- Python setup
- Dependency installation
- Unit test execution
- Docker build validation

---

## 🧭 Roadmap Connection

This project is part of my DevOps learning and portfolio roadmap:

- Start with a simple Flask app
- Add CI/CD automation using GitHub Actions
- Containerize the app using Docker
- Deploy to cloud infrastructure (AWS)
- Manage infrastructure using Terraform

Together with my Terraform AWS repo, this demonstrates end-to-end DevOps capability.

---

## 🔐 Security Best Practices

- No secrets stored in code
- GitHub Actions uses secure runners
- Dockerfile follows minimal base image approach
- Dependencies pinned in requirements.txt

---

## 🔮 Future Enhancements

- Add CD pipeline to deploy Docker image to AWS ECS/ECR
- Add Terraform module to provision ECS infrastructure
- Add CloudWatch logging and monitoring
- Add automated Docker image scanning
- Add staging and production environments

---

## 📬 Contact

If you'd like help building similar CI/CD pipelines or cloud infrastructure, feel free to reach out.

---

## 🌐 Portfolio

**Visit my portfolio:** [shivdevops.cloud](https://shivdevops.cloud)

Explore more projects and infrastructure solutions that demonstrate my expertise in DevOps, Cloud Architecture, and Infrastructure as Code.