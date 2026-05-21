# k8s-n8n-pocharlies

n8n — workflow automation. DB: shared postgres + shared redis

## Cluster
- **Master**: x86 ubuntu (192.168.50.142), k3s v1.32.5
- **Workers**: nvidia-dgx (dgx1 ARM64), gx10-ec3d (dgx2 ARM64), sauvage (WireGuard edge)

## GitOps
Gestionado por ArgoCD desde [k8s-gitops-pocharlies](https://github.com/pocharlies/k8s-gitops-pocharlies).
