# Hey, I'm Adrián

Sysadmin L2 at an MSP in Barcelona. I manage 350+ VMs, run mail migrations, and handle multi-tenant identity and security operations across VMware vSphere, Proxmox, Citrix Cloud, and Microsoft 365.

At work, I designed and I'm leading the implementation of a company-wide GitOps platform with GitLab CI, Terraform, Ansible, HashiCorp Vault, and Kubernetes.

At home, I build infrastructure from scratch and break it on purpose.

British and Spanish. Native in both.

---

## Things I've Built

### homelab-as-code *(in progress)*

Everything I need to rebuild my entire homelab from scratch if the hardware burns tomorrow. Proxmox VE hypervisor, 12 LXC/VM services, 3-node K3s cluster on Raspberry Pi, GitOps pipelines, observability, and networking, all as code from a single Ubuntu Server VM.

https://github.com/AdrianStudio/homelab-as-code

### k3s-manifest-generator

Python CLI that generates Kubernetes manifests (Deployment, Service, Ingress) via interactive prompt and commits them directly to Gitea, triggering ArgoCD auto-sync to K3s. Cut new service deployments from 15 to 20 minutes of manual YAML to under 2 minutes.

https://github.com/AdrianStudio/k3s-manifest-generator

### aws-core-terraform

Reusable AWS infrastructure deployed with Terraform: VPC with public and private subnets across 2 AZs, EC2, S3 with AES256 encryption, and IAM with least-privilege policies. The entire stack can be created or destroyed with a single command. Complemented with a boto3 Python script for programmatic resource inspection.

https://github.com/AdrianStudio/aws-core-terraform

### argocd-k3s-gitea

Step-by-step guide to deploy ArgoCD on K3s and connect it with a self-hosted Gitea instance. Written because every guide I found assumed GitHub or a managed cluster.

https://github.com/AdrianStudio/argocd-k3s-gitea

---

## The Homelab

Proxmox VE on an HP EliteDesk. 12 LXC containers and VMs running Gitea, Nextcloud, Vaultwarden, Pi-hole, Uptime Kuma, Jellyfin, and more. A 3-node K3s cluster on Raspberry Pi 4 with ArgoCD, Prometheus, Grafana, and Ingress NGINX. Tailscale mesh VPN and Cloudflare Tunnel on tamargo.dev.

I use it daily to test infrastructure changes before applying them at work.

---

## Certifications

| Cert | Status |
|------|--------|
| AZ-900: Microsoft Azure Fundamentals | Obtained |
| AZ-104: Microsoft Azure Administrator | In Progress |
| CKA: Certified Kubernetes Administrator | In Progress |
| Cambridge C1 Advanced (English) | Obtained |

---

## Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/adrian-tamargo)
[![Email](https://img.shields.io/badge/tadri05m@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:tadri05m@gmail.com)
