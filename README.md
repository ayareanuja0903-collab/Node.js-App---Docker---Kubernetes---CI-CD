# 🚀 Node.js Kubernetes CI/CD Project

This project demonstrates:

- Node.js App
- Docker
- Kubernetes
- GitHub Actions CI/CD

## Run locally
npm install
node server.js

## Docker
docker build -t nodejs-app .
docker run -p 3000:3000 nodejs-app

## Kubernetes
kubectl apply -f k8s/

Access:
http://<NodeIP>:30007
