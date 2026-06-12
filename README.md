# GitOps Workflow using ArgoCD on Kubernetes
## Objective

Implement GitOps by syncing Kubernetes deployment states directly from a Git repository using ArgoCD.

---

## Tools Used

- Kubernetes (Minikube)
- ArgoCD
- GitHub
- Docker
- Git Bash

---

## Architecture

Developer → GitHub → ArgoCD → Kubernetes Cluster

---

## Project Workflow

1. Install Minikube and Kubernetes.
2. Install ArgoCD.
3. Create Kubernetes manifests.
4. Push manifests to GitHub.
5. Connect ArgoCD with GitHub repository.
6. Enable Auto Sync.
7. Update manifests through Git commits.
8. ArgoCD automatically deploys changes.

---

## Files

### deployment.yaml

Contains Kubernetes Deployment configuration.

### service.yaml

Contains Kubernetes Service configuration.

---

## Features

- GitOps Workflow
- Automatic Deployment
- Auto Sync
- Self Healing
- Version Controlled Infrastructure

---

## Verification

```bash
kubectl get pods

kubectl get svc
```

---

## Screenshots

### ArgoCD Dashboard

<img width="1808" height="883" alt="Screenshot 2026-06-12 223127" src="https://github.com/user-attachments/assets/d69cf799-2efe-488c-b372-b65e7ff2e2c6" />

### Application Sync

<img width="1895" height="889" alt="Screenshot 2026-06-12 223342" src="https://github.com/user-attachments/assets/c5a098b2-597d-48ab-91fa-72e7bfb400a8" />

### updated nginx image version 1.25 to 1.26

<img width="1910" height="880" alt="Screenshot 2026-06-12 210629" src="https://github.com/user-attachments/assets/15255857-ed96-46ab-82f2-ad5722ce6871" />

### updated replicas from 2 to 4 

<img width="1471" height="876" alt="Screenshot 2026-06-12 215056" src="https://github.com/user-attachments/assets/1bcd6aba-d45f-434d-a9ca-60bba28cb945" />

### video explaining GitOps workflow

https://github.com/user-attachments/assets/7e8c81ca-8af9-468c-aa96-8993cecffe30
