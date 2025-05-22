# Kubernetes Ingress Deployment

Quick setup for online shop with Nginx/Apache services on EC2 (54.161.250.53).

## 🚀 Quick Start
```bash
git clone git@github.com:harisamjad0158/ingress.git
cd ingress
kubectl apply -f all-in-one.yml
kubectl apply -f ingress.yml

🌐 Access Services
Online Shop: http://IP/shop

Nginx: http://IP/nginx

Apache: http://IP/apache

📂 Files
all-in-one.yml - Deployments & services

ingress.yml - Ingress rules

kind-config.yaml - Cluster config

🔒 Security
Open ports 80/443 on EC2

Add TLS for production

kubectl get pods -A
kubectl logs -n ingress-nginx [pod-name]


