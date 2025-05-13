# GitOps-based Fintech Payment Gateway

This is a simple GitOps deployment of a payment gateway microservice using ArgoCD and Helm on Kubernetes (K3s) on an AWS EC2 instance.

## Stack

- Kubernetes (K3s)
- Helm
- ArgoCD
- AWS EC2
- GitHub

## Environments

- `dev`
- `staging`
- `prod`

## Deployment Flow

1. Git push to the repo
2. ArgoCD watches repo
3. Helm deploys app to the correct namespace/environment

## Ports

- ArgoCD UI: `http://18.118.7.3:30080`
- Dev App: `http://18.118.7.3:30001`
- Staging App: `http://18.118.7.3:30002`
- Prod App: `http://18.118.7.3:30003`


