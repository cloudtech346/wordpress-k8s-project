# 🚀 WordPress on Kubernetes (AWS EC2)

## 📌 Project Overview
This project demonstrates deployment of WordPress with MySQL on Kubernetes cluster using AWS EC2.

## 🛠 Architecture
- Kubernetes Cluster (1 Master + 2 Workers)
- MySQL Deployment + PVC
- WordPress Deployment
- NodePort Service

## ⚙️ Setup Steps
```bash
kubectl apply -f pv.yaml
kubectl apply -f mysql.yaml
kubectl apply -f wordpress.yaml
# WordPress on Kubernetes (AWS EC2)

## Access
http://<public-ip>:30007
