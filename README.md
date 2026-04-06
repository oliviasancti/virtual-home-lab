# Virtual Home Lab

A documented home lab and cybersecurity environment built to develop hands-on experience across infrastructure, networking, security, DevOps, and cloud-native systems.

This repository tracks my lab architecture, infrastructure setup, and hands-on projects performed in a segmented, production-like environment.

---

## Purpose

This lab is designed to simulate real-world infrastructure and security workflows while building practical experience in:

- Virtualization and infrastructure management
- Network segmentation and firewall design
- Storage, backups, and shared datastores
- Monitoring, logging, and observability
- Cloud-native deployments and GitOps workflows
- Security testing, attack simulation, and detection
- Automation and infrastructure experimentation

---

## Core Architecture

- **Firewall & Routing**: pfSense with VLAN segmentation for traffic isolation, access control, and security zoning  
- **Networking**: Managed switching and access points supporting segmented lab, management, and service networks  
- **Storage**: TrueNAS (Ugreen NAS) providing centralized storage, backups, and shared datastores (NFS/SMB)  

---

## Compute & Virtualization

- **Hypervisor**: Proxmox cluster (Lenovo ThinkCentre M910q nodes)  
- **Workloads**:
  - Ubuntu VMs for services and tooling  
  - Windows Server for Active Directory and identity management  
  - Security-focused VMs for lab simulations  
- **Capabilities**:
  - Snapshotting and rollback for testing  
  - Shared storage integration for replication  
  - High availability and infrastructure experimentation  

---

## Containers & Orchestration

- **Container Platform**: Docker  
- **Orchestration**: Kubernetes cluster (Raspberry Pi-based)  

### Deployed Services:
- **Grafana** → monitoring and observability dashboards  
- **MongoDB** → stateful application workloads  
- **ArgoCD** → GitOps-based deployment workflows  
- **Pi-hole** → containerized DNS filtering for network-wide control  

---

## Security & Monitoring

- VLAN-based segmentation to support:
  - lab isolation  
  - attack simulation environments  
  - zero-trust concepts  

- Centralized logging and monitoring pipelines for:
  - system visibility  
  - detection workflows  
  - alerting and analysis  

- Environment designed for:
  - blue team monitoring  
  - ethical hacking labs  
  - incident simulation and response  

---

## Operations & Management

- Rack-mounted setup with integrated display and KVM access  
- Optimized for:
  - small-form-factor enterprise hardware  
  - power efficiency and airflow  
- Centralized visibility via:
  - **Glance dashboard** (single-pane-of-glass monitoring)  

---

## Skills Demonstrated

- **Virtualization & Infrastructure**: Proxmox clustering, VM lifecycle management  
- **Networking & Security**: pfSense, VLAN segmentation, firewall rule design  
- **Storage & Systems**: TrueNAS, shared storage, backup strategies  
- **Cloud-Native & DevOps**: Docker, Kubernetes, ArgoCD, GitOps workflows  
- **Monitoring & Observability**: Grafana, centralized logging pipelines  
- **Cybersecurity**: network isolation, attack simulation environments, detection workflows  
- **Automation & Experimentation**: infrastructure testing, repeatable lab scenarios  
- **Documentation & System Design**: architecture planning, structured lab documentation  

---

## Lab Stack

- **Hypervisor**: Proxmox  
- **Firewall/Router**: pfSense  
- **Storage**: TrueNAS (Ugreen NAS)  
- **Compute Nodes**: Lenovo ThinkCentre M910q cluster  
- **Container Platform**: Docker  
- **Orchestration**: Kubernetes (Raspberry Pi cluster)  
- **Monitoring**: Grafana  
- **GitOps**: ArgoCD  
- **Database**: MongoDB  
- **DNS Filtering**: Pi-hole  
- **Dashboard**: Glance  

---

## Repository Structure

docs/            -> topology, network design, setup documentation
infrastructure/  -> Proxmox, pfSense, AD, and system configurations
projects/        -> lab projects, experiments, and reports
notes/           -> lab journal, troubleshooting, and changes
scripts/         -> automation and tooling
assets/          -> diagrams, rack photos, screenshots
---

## References
- [Proxmox VE Documentation](https://pve.proxmox.com/wiki/Main_Page)  
- [pfSense Setup Guide](https://docs.netgate.com/pfsense/en/latest/install/install-guide.html)  
- [Windows Server AD Docs](https://docs.microsoft.com/en-us/windows-server/identity/active-directory-domain-services/)  
- [Pi-hole DNS Setup](https://pi-hole.net/)  

---

## License
This repository is for **professional portfolio and educational purposes only**.
