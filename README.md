# Jenkins CI/CD Pipeline for Java Application Deployment

## Project Overview
This project demonstrates a complete CI/CD pipeline for deploying a Java application using Jenkins, Docker, and Kubernetes.

The pipeline automates:
- Application build process
- Docker image creation
- Kubernetes deployment
- Service exposure

---

## Technologies Used

- Jenkins
- Docker
- Kubernetes
- Tomcat
- Java
- YAML
- GitHub

---

## Project Architecture

Developer → GitHub → Jenkins Pipeline → Docker Build → Kubernetes Deployment

---

## Files Included

| File Name | Description |
|---|---|
| Jenkinsfile | Jenkins CI/CD pipeline configuration |
| Dockerfile | Docker image build instructions |
| deployment.yaml | Kubernetes deployment configuration |
| service.yaml | Kubernetes service configuration |

---

## CI/CD Workflow

1. Developer pushes code to GitHub
2. Jenkins triggers pipeline automatically
3. Docker image is built
4. Image is deployed to Kubernetes cluster
5. Application becomes accessible through service

---

## Kubernetes Deployment

Deployment includes:
- Replica management
- Containerized Java application
- LoadBalancer service exposure

---

## Future Enhancements

- Helm charts
- Monitoring with Prometheus & Grafana
- Ingress controller setup
- SSL integration
- AKS/GKE deployment
- GitHub Actions integration

---

## Author

Narayana Rao  
DevOps Engineer | Kubernetes | Azure | AWS | Docker | Jenkins | Linux
