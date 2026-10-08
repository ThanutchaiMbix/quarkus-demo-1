# quarkus-demo-1

Quarkus (Camel) service created by Backstage Software Template

Quarkus + Apache Camel service พร้อม Kubernetes manifests (`k8s/`) และ ArgoCD Application (`argocd/`) สำหรับ GitOps

## Quick start

```bash
mvn quarkus:dev          # dev mode
docker build -t image-registry.openshift-image-registry.svc:5000/demo/quarkus-demo-1 .   # build container image
```

ดูรายละเอียด Minikube/ArgoCD ทั้งหมดที่ [docs/index.md](docs/index.md)
