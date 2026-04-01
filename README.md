# 🚀 CI/CD Demo Project with Jenkins & Docker

This is a simple Node.js demo application showcasing a complete **CI/CD pipeline** using **Jenkins** and **Docker**.
The pipeline automatically builds and deploys the application whenever changes are pushed to the repository.

---

## 📦 Project Structure

```
.
├── app.js
├── package.json
├── Dockerfile
├── .gitignore
└── README.md
```

---

## ⚙️ Tech Stack

* Node.js
* Docker
* Jenkins
* GitHub

---

## 🔄 CI/CD Pipeline Stages

The Jenkins pipeline performs the following steps:

1. **Clone** – Pulls the latest code from GitHub
2. **Build** – Builds Docker image from Dockerfile
3. **Deploy** – Runs container from built image

---

## 🐳 Docker Build

The application is containerized using Docker.

To build manually:

```
docker build -t cicd-project .
```

To run container:

```
docker run -p 8080:8080 cicd-project
```

---

## 🔧 Jenkins Pipeline

Pipeline is configured to:

* Trigger on code changes
* Build Docker image
* Deploy automatically

---

## ▶️ Application

Once deployed, the app runs on:

```
http://localhost:8080
```

---

## 🎯 Purpose

This project demonstrates:

* Basic CI/CD workflow
* Jenkins pipeline setup
* Docker containerization
* Automated deployment

---

## 👤 Author

RISHAb
