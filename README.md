<p align="center">
  <img src="assets/architecture-diagram.png" width="900"/>
</p>

<h1 align="center">Baratul Khan</h1>
<h3 align="center">Infrastructure & Operations Engineering</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Windows_Server-Active_Directory-0078D6?style=for-the-badge&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-Systems_Engineering-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Networking-VLAN_•_Routing_•_NAT-1BA0D7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Security-Operational_Hardening-CC0000?style=for-the-badge"/>
</p>

---

# 🏗 Enterprise Infrastructure Simulation Environment

This repository represents a structured enterprise-style infrastructure environment built using virtualization to simulate real-world IT operations.

The objective is not configuration practice — it is operational validation.

The environment is designed to model:

- Centralized identity management
- Network segmentation and traffic control
- Service deployment and failure testing
- Log-driven troubleshooting
- Security enforcement and validation
- Controlled misconfiguration and recovery

Each system is built, tested, broken, analyzed, and restored.

---

# 🧱 Architecture Overview

The environment includes:

- Windows Server 2022 (Domain Controller)
- Windows 10 Enterprise Client
- Linux Server (Ubuntu / Debian)
- Segmented VLAN network architecture
- DNS and DHCP services
- NAT and routing configuration
- Host-based and network-based security controls
- Log monitoring and traffic inspection

Architecture diagram:

![Infrastructure Diagram](assets/architecture-diagram.png)

---

# 🔐 Identity & Access Management

🔗 https://github.com/InfoSec01/windows-server-lab/blob/main/README.md

- Active Directory Domain Services deployment
- Organizational Unit design based on business roles
- Group Policy design and inheritance modeling
- NTFS and shared permission conflict testing
- DNS internal resolution validation
- Authentication failure troubleshooting
- Controlled policy rollback and recovery

Focus: Stability, identity control, and structured access governance.

---

# 🐧 Linux Systems Engineering

🔗 https://github.com/InfoSec01/linux-administration/blob/main/README.md

- User and group lifecycle control
- SSH hardening and secure remote administration
- Service lifecycle management (systemctl)
- Log analysis using journalctl and syslog
- Cron-based backup automation
- Permission modeling and privilege separation

Focus: Service reliability, access control, and operational continuity.

---

# 🌐 Network Operations

🔗 https://github.com/InfoSec01/Network-Administration/blob/main/README.md

- VLAN segmentation strategy
- Inter-VLAN routing
- NAT boundary configuration
- Access Control List implementation
- Packet inspection using Wireshark
- Traffic validation and segmentation testing

Focus: Controlled traffic flow, isolation, and diagnostic visibility.

---

# 🛡 Infrastructure Security Operations

🔗 https://github.com/InfoSec01/information-security/blob/main/README.md

- Host-based firewall enforcement
- IDS deployment (Snort)
- Web application hardening (ModSecurity)
- Log-based anomaly detection
- Attack surface reduction
- Security control validation testing

Focus: Layered security and detection capability.

---

# 🔎 Operational Methodology

The environment is built using an operations-first approach:

- Layered troubleshooting model  
  (Network → System → Service → Identity)

- Controlled failure simulation

- Log-driven root cause analysis

- Recovery validation after misconfiguration

- Documentation aligned to internal IT standards

---

# 📊 Scope Alignment

This infrastructure portfolio aligns with responsibilities commonly seen in:

- Infrastructure Engineer
- Systems Administrator
- Windows / Linux Administrator
- IT Operations Engineer
- Technical Operations Analyst
- NOC Engineer
- Infrastructure Support Engineer
- Identity & Access Administrator
- Network Support Engineer
- Platform Support Engineer

---

# 📫 Contact

baratulkhan@gmail.com

---

<p align="center">
  Reliable infrastructure is engineered, validated, monitored, and secured.
</p>
