# Hey, I'm Adrián

Sysadmin L2 at an MSP in Barcelona. I manage 350+ VMs, run mail migrations, and handle multi-tenant identity and security operations across VMware vSphere, Proxmox, Citrix Cloud, and Microsoft 365.

At work, I designed and I'm leading the implementation of a company-wide GitOps platform with GitLab CI, Terraform, Ansible, HashiCorp Vault, and Kubernetes.

At home, I build infrastructure from scratch and break it on purpose.

British and Spanish. Native in both.

---

## Things I've Built

### homelab-as-code *(in progress)*

Everything I need to rebuild my entire homelab from scratch if the hardware burns tomorrow. Three bare-metal Proxmox nodes (EliteDesk 600 G2 + two ProDesk 400 G3s), 12 LXC/VM services, a K3s cluster, GitOps pipelines, observability, and networking, all as code from a single repo. Three layers: Terraform creates the VMs, Ansible configures them, ArgoCD deploys the services.

https://github.com/AdrianStudio/homelab-as-code

### azure-lab-projects *(in progress)*

Architecture-focused Azure labs built while studying for the AZ-305 certification. Each project starts with a real business scenario, walks through the design decisions with their trade-offs, and ends with a working deployment. First completed project covers RBAC and Key Vault, including the management plane vs data plane separation that most teams get wrong.

https://github.com/AdrianStudio/azure-lab-projects

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

Three bare-metal nodes: an HP EliteDesk 600 G2 as Proxmox master and two HP ProDesk 400 G3s as workers. 12 LXC containers and VMs running Gitea, Nextcloud, Vaultwarden, Pi-hole, Uptime Kuma, and more. K3s cluster with ArgoCD syncing from GitHub, Prometheus, Grafana, Traefik, and Ingress NGINX. Tailscale mesh VPN and Cloudflare Tunnel on tamargo.dev.

I use it daily to test infrastructure changes before applying them at work.

---

## Certifications

| Cert | Status |
|------|--------|
| AZ-900: Microsoft Azure Fundamentals | Obtained |
|
