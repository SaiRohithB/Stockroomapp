# Stockroom

Stockroom is a full-stack inventory management application built to manage stock items, products, and backend data through a web interface.

This project was created as a learning project to understand how frontend, backend, database, Docker, and Kubernetes work together in a real application deployment.

---

## Features

- Web-based stockroom/inventory interface
- Backend REST API
- Database connectivity
- Dockerized frontend and backend
- Kubernetes deployment support
- Nginx-based frontend serving
- Backend service routing through Kubernetes Service / Ingress

---

## Tech Stack

### Frontend
- React
- Vite
- Nginx

### Backend
- Java / Spring Boot

### Database
- PostgreSQL / AWS RDS PostgreSQL

### DevOps / Deployment
- Docker
- Kubernetes
- Minikube
- Ingress
- Nginx

---

## Project Structure

```text
stockroom/
├── backend/
│   ├── Dockerfile
│   ├── app.jar
│   └── application.properties
│
├── frontend/
│   ├── Dockerfile
│   ├── nginx.conf
│   ├── package.json
│   └── src/
│
├── k8s/
│   ├── backend-deployment.yaml
│   ├── backend-service.yaml
│   ├── frontend-deployment.yaml
│   ├── frontend-service.yaml
│   └── ingress.yaml
│
└── README.md
