#  Secure Infrastructure Architecture – Health Insurance (HDS / RGPD)

##  Professional Infrastructure & Cybersecurity Project

This repository showcases a **realistic, enterprise-grade infrastructure architecture**
designed for a **health insurance organization operating at national and international scale**.

The project focuses on **security, resilience, compliance (RGPD / HDS)** and operational efficiency,
with constraints comparable to real-world production environments.

---

## Project Context

- **Industry**: Healthcare / Health Insurance
- **Scope**: National + International
- **Users**: ~10,000
- **Sites**: 500+ agencies
- **Criticality**: High (sensitive health data)
- **Availability target**: 99.9%+

The goal was to **respond to a strategic RFP** by proposing a complete, secure and scalable infrastructure.

---

##  Key Design Principles

✔ Security by design  
✔ Defense in depth  
✔ Zero Trust approach (ZTNA)  
✔ High Availability & Business Continuity  
✔ Regulatory compliance (RGPD, HDS)  
✔ Centralized governance with local performance  

---

##  Global Architecture Overview

### Datacenters
- **2 HDS-certified datacenters** (Primary + Disaster Recovery)
- Active/Passive architecture
- RTO: 4h | RPO: 15 min
- Cloud extension on **SecNumCloud**

### Network Segmentation
- Admin Zone (Bastion / Management)
- Production Zone
- DMZ (public services)
- Strict East/West traffic filtering

---

##  Security Architecture

### Perimeter & Network Security
- Fortinet **FortiGate** (WAN / DMZ / Internal Segmentation)
- IPsec VPN (AES-256, certificate-based auth)
- SD-WAN for agencies

### Application Security
- **FortiWeb WAF**
- Reverse proxy & load balancing
- Protection against OWASP Top 10

### Access Control
- Bastion (Apache Guacamole)
- ZTNA for remote users
- MFA (FortiToken)

---

##  Monitoring, Logs & Operations

- **Zabbix** – Infrastructure & service monitoring
- **Syslog** – Centralized logging
- **FortiAnalyzer** – Security analytics
- Full traceability for audits (HDS / RGPD)

---

##  Agencies & Remote Sites

- 500+ agencies
- Dual Internet links per site
- Encrypted tunnels to central DC
- Local firewalling & traffic optimization

---

##  Economic & Operational Model

- Predominantly **OpEx**
- Hardware + licenses + support included
- Cost optimization through central management
- Designed for easy onboarding of new sites

---

##  Repository Content

- `docs/` → Detailed architecture & compliance documents
- `diagrams/` → Network & security diagrams
- `configs/` → Example firewall, VPN & segmentation configs

> ⚠️ Configurations are anonymized and simplified for demonstration purposes.

---

##  About Me

I am a **network & cybersecurity-oriented IT professional**, focused on:
- Secure infrastructure design
- Network segmentation & firewalling
- VPN & remote access
- Compliance-driven architectures (HDS, RGPD)
- Real-world operational constraints

 **Open to opportunities** in:
- Network Engineering
- Infrastructure Engineering
- Cybersecurity / SOC / Blue Team
- Cloud & Hybrid Infrastructure

---

## 📜 Disclaimer

This is a **portfolio project**.
No real customer data, credentials or production configurations are exposed.
