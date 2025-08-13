# virtual-home-lab
Home lab setup, topology notes, VM setup, racks and projects 

## Overview
This repository documents my **virtual home lab environment** and related projects, showcasing my **organization, documentation skills, and project planning**.  
The lab serves as a hands-on environment for cybersecurity, cloud computing, and IT infrastructure experiments, while also demonstrating **structured project management**.

---

## Skills Demonstrated
- Virtualization & VM Management (Proxmox, Windows Server, Ubuntu)  
- Network Design & Firewall Configuration (pfSense, VLANs, Switch Management)  
- Cloud Security Fundamentals (AWS, IAM, misconfiguration detection)  
- Cybersecurity & Pentesting (SIEM setup, vulnerability scanning, k3s experimentation)  
- Project Planning & Documentation (Milestones, task lists, diagrams)  
- Technical Communication & Professional Documentation  

---

## Physical & Virtual Lab Highlights
### Physical Layer
- **Rack 1 – Core Lab**
  - Patch Panel, Brush Panel
  - 2U GeekPi Screen / KVM
  - Proxmox Server (VM Host)
  - pfSense Server
  - Ubuntu Server & Raspberry Pi
  - Managed Switch
- **Rack 2 – Power & Storage**
  - UPS, NAS
  - k3s Cluster Nodes (Kubernetes experiments)
- **External Devices**
  - Gaming PC (remote VM management)
  - Odyssey G9 Monitor
  - TP-Link EAP610 Wi-Fi 6 Access Point (WAN connectivity, PoE powered)

### Virtual Layer
- Proxmox VMs:
  - Windows Server (Active Directory)
  - Ubuntu Server (utilities, SIEM testing)
  - pfSense (optional VM)
- VLAN Segmentation:
  - VLAN 10: Lab VMs
  - VLAN 20: Management / Firewall
  - VLAN 30: DNS / IoT (Pi-hole)
- k3s Cluster (Rack 2) for lightweight Kubernetes workloads
- Raspberry Pi running Pi-hole for DNS / ad-blocking

---

## Project Roadmap (Sample)

| Month | Track | Project Title | Tools | Status |
|-------|-------|---------------|-------|--------|
| 1–2   | Home Lab & Core Infra | Build Virtual Home Lab w/ pfSense + AD | Proxmox, Windows Server, Ubuntu, pfSense | Planned |
| 1–2   | Home Lab & Core Infra | SIEM Setup & Log Monitoring | Wazuh/Splunk, ELK, Winlogbeat | Planned |
| 1–2   | Cloud Security | AWS Basic Architecture + IAM + Misconfig Report | AWS Free Tier, EC2, IAM | Planned |
| 3–4   | Pentesting | Vulnerability Scan + Risk Report | OpenVAS, Nessus, Nmap | Planned |
| 3–4   | Pentesting | Juice Shop OWASP Exploits & Report | Juice Shop, Burp Suite | Planned |
| 3–4   | Pentesting | Red Team Report (Metasploit + DVWA) | Kali, Metasploit, DVWA | Planned |

> Full project roadmap and monthly notes are included in the corresponding folders (`Month-1-2-Build-Virtual-Home-Lab/`, `Month-1-2-SIEM-Setup/`, etc.).

---

## Diagrams
- Physical Rack Layouts & Patch Panel Mapping  
- Virtual Network Topology & VLAN Segmentation  
- Stored in `/Diagrams` folder as ASCII Markdown or PNG images  

---

## How This Demonstrates Professional Skills
1. **Organization** – Structured notes, diagrams, and project roadmaps.
2. **Documentation Skills** – Clear step-by-step setup guides, VLAN and VM configurations, checklists.
3. **Project Planning** – Monthly milestones, tool lists, status tracking, and notes linked to each project.
4. **Technical Expertise** – Virtualization, networking, cloud, cybersecurity, and AI projects all documented clearly for a professional audience.

---

## References
- [Proxmox VE Documentation](https://pve.proxmox.com/wiki/Main_Page)  
- [pfSense Setup Guide](https://docs.netgate.com/pfsense/en/latest/install/install-guide.html)  
- [Windows Server AD Docs](https://docs.microsoft.com/en-us/windows-server/identity/active-directory-domain-services/)  
- [Pi-hole DNS Setup](https://pi-hole.net/)  

---

## License
This repository is for **professional portfolio and educational purposes only**.
