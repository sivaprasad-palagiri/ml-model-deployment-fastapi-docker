# ML Model Deployment with FastAPI & Docker

Production-style Machine Learning model deployment project using FastAPI, Docker, and AWS-ready architecture.

---

# Project Overview

This project demonstrates how to deploy a Machine Learning model as a production-ready REST API using FastAPI and containerize it with Docker.

The goal of this project is to simulate a real-world MLOps and cloud deployment workflow.

---

# Tech Stack

## Backend
- FastAPI
- Python

## Machine Learning
- Scikit-learn
- Pickle

## DevOps & Deployment
- Docker
- GitHub
- Linux

## Cloud (Planned)
- AWS EC2
- Nginx
- CI/CD Pipeline
- Kubernetes
- Terraform

---

# Project Structure

```bash
ml-model-deployment-fastapi-docker/
│
├── app/
│   ├── main.py
│   ├── train_model.py
│   ├── model.pkl
│   └── requirements.txt
│
├── Dockerfile
├── README.md
├── LICENSE
└── .gitignore
```

---

# Features

- ML model training
- REST API with FastAPI
- Docker containerization
- Production-style project structure
- Cloud deployment ready

---

# Run Locally

## Clone Repository

```bash
git clone https://github.com/sivaprasad-palagiri/ml-model-deployment-fastapi-docker.git
```

## Move into Project

```bash
cd ml-model-deployment-fastapi-docker
```

## Install Dependencies

```bash
pip install -r app/requirements.txt
```

## Run FastAPI Application

```bash
uvicorn app.main:app --reload
```

---

# Docker Build

## Build Docker Image

```bash
docker build -t ml-api .
```

## Run Docker Container

```bash
docker run -p 8000:8000 ml-api
```

---

# API Endpoint

## Health Check

```bash
GET /
```

## Prediction Endpoint

```bash
POST /predict
```

---

# Future Improvements

- AWS EC2 deployment
- CI/CD with GitHub Actions
- Kubernetes deployment
- Monitoring with Prometheus & Grafana
- Terraform Infrastructure as Code
- Model versioning
- Production logging

---

# Learning Goals

This project is part of my journey toward:

- Cloud Engineering
- DevOps
- AI Infrastructure
- MLOps
- Platform Engineering

---

# Author

Siva Prasad Palagiri

Dubai, UAE

LinkedIn:
https://www.linkedin.com/in/sivaprasad-palagiri

<img width="2936" height="1626" alt="image" src="https://github.com/user-attachments/assets/61b0ab9d-848e-466c-9c56-760003ee879c" />

