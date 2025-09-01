# Ansible public k3s playbook for single-node k3s Cluster

This repository was created for a **test assignment**.  
It provisions a **single-node k8s cluster** with preconfigured system components.

## What’s Included

- **kube-proxy** — network proxy for Kubernetes services  
- **CoreDNS** — DNS service for Kubernetes  
- **CNI** — container network interface plugin  
- **Traefik** — built-in ingress controller  

## Requirements

- Linux host 
- Ansible installed on the local machine  
- SSH access to the target node with `root` or `sudo` privileges without password authorization
