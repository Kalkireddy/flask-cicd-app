 A minimal Flask web application fully containerized with Docker, designed for DevOps practice, CI/CD integration, and freelance portfolio.

## 🚀 Features

- Minimal Flask web app
- Containerized with docker 
- Clean code structure
- Ideal for Devops CI/CD demo


## 🧱 Tech Stack

- Python 3
- Fllask 3.1.2
- Docker

## 📁 Project Structure

## 🛠️ Getting Started

### Prerequisites
- Python 3.9+
- Docker (for containerization)

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

## 🐳 Run with Docker

```bash
# Clone the repository
git clone git@github.com:Kalkireddy/flask-cicd-app.git
cd flask-cicd-app

# Build the Docker image
docker build -t flask-cicd-app .

# Run the Docker container
docker run -p 5000:5000 flask-cicd-app
App will be available at: http://localhost:5000