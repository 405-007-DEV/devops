# argocd
GitOps Continuous Delivery for Kubernetes

**CAUTION: 차트가 업그레이드되어 현재 values.yaml을 사용하려면 버전을 명시해줘야 함**

## Base Chart
https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd

## Installation
```bash
helm repo add argo https://argoproj.github.io/argo-helm

helm install argocd -n argocd -f values.yaml argo/argo-cd --version 5.46.7
```
