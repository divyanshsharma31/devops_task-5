# devops_task-5
# Kubernetes Deployment and Service using Minikube

## 📌 Task Overview
This task demonstrates creating and deploying an application in Kubernetes using **Minikube** on Windows.  
We will:
1. Start a local Kubernetes cluster using Minikube.
2. Create a **Deployment** for an NGINX web server.
3. Create a **Service** to expose the deployment.
4. Access the application through the NodePort.

---

## 🛠 Prerequisites
- **Docker Desktop** installed and running
- **Minikube** installed
- **kubectl** CLI installed
- VS Code or any text editor

---

## 🚀 Steps Performed

### 1️⃣ Start Minikube
```bash
minikube start --driver=docker
