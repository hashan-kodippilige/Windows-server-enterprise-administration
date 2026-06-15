# Enterprise Windows Server infrastructure project featuring Active Directory, DNS, DHCP, Group Policy, File & Print Services, Storage Spaces, Backup & Recovery, and enterprise network architecture.

## Overview

This project demonstrates the design, deployment, administration, and security management of a Windows Server enterprise environment using VMware Workstation.

The lab simulates a corporate Active Directory infrastructure supporting centralized authentication, DNS, DHCP, file services, print services, storage management, backup and recovery, and Group Policy administration.

---
## Network Architecture

The following diagram illustrates the enterprise Active Directory environment deployed in this project.

<img width="1448" height="1086" alt="Diagram" src="https://github.com/user-attachments/assets/5a9705dd-efcf-4e48-971b-48ccd49f425a" />

## Environment

### Virtual Infrastructure

- VMware Workstation
- Windows Server 2019
- Windows 10 Enterprise Workstations
- Active Directory Domain Services (AD DS)

### Domain

```text
AD.ACME.EDU
```

### Core Servers

| Server | Role |
|----------|----------|
| AcmePDC01 | Primary Domain Controller |
| AcmePDC02 | Secondary Domain Controller |
| AcmeWks1001 | Domain Workstation |

---

## Technologies Implemented

### Active Directory

- Domain Controller deployment
- Organizational Unit (OU) design
- User account management
- Security groups
- Distribution groups
- Home directories

### DHCP

- DHCP scope creation
- DHCP authorization
- DHCP reservations
- Dynamic IP assignment

### DNS

- Forward lookup zones
- Reverse lookup zones
- Host records
- Alias records (CNAME)
- MX records
- Name resolution testing

### File Services

- Shared folders
- NTFS permissions
- Home directories
- Department shares
- Role-based access control

### Print Services

- Network printer deployment
- Printer security groups
- Restricted printer access
- Printer management

### Storage Management

- Storage Spaces
- Virtual disks
- RAID implementation
- Volume management

### Backup and Recovery

- Windows Server Backup
- Backup scheduling
- File recovery
- Disaster recovery testing

### Group Policy

- Password policies
- Account lockout policies
- Kerberos policies
- Login banners
- Desktop standardization
- Screen timeout enforcement
- Local account hardening
- Software deployment

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Management
- Group Policy Administration
- DNS & DHCP Management
- Identity & Access Management (IAM)
- Network Services Administration
- File Server Administration
- Storage Management
- Backup & Disaster Recovery
- Security Hardening
- Enterprise IT Operations

---

## Key Accomplishments

### Domain Services

- Installed Active Directory Domain Services
- Promoted Windows Server to Domain Controller
- Configured DNS and DHCP services

### Security Administration

- Implemented password complexity policies
- Configured account lockout policies
- Applied security-focused Group Policies
- Renamed and disabled default local accounts

### Enterprise File Services

- Created departmental file shares
- Configured NTFS permissions
- Implemented role-based access controls
- Created user home directories

### Backup & Recovery

- Configured Windows Server Backup
- Simulated storage failures
- Tested RAID recovery procedures
- Successfully restored data from backups

---

## Repository Contents

```text
README.md
Acme-Lab-01.pdf
Acme-Lab-02.pdf
Acme-Lab-03.pdf
Acme-Lab-04.pdf
Acme-Lab-05.pdf
Acme-Lab-06.pdf
Acme-Lab-07.pdf
Acme-Lab-08.pdf
Network-Topology.png
Screenshots/
```

---

## Author

Hashan Kodippilige
Master of Science in Cybersecurity
Minnesota State University Moorhead

Splunk Dashboard Developer | Network Security | SIEM | Digital Forensics


# 🖥️ Enterprise Windows Server Administration

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20Server%202019-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Tool-VMware%20Workstation-607078?style=for-the-badge&logo=vmware&logoColor=white" />
  <img src="https://img.shields.io/badge/Service-Active%20Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Enterprise%20IT-4B4B4B?style=for-the-badge&logo=microsoft&logoColor=white" />
</p>

> 🏢 Enterprise-grade Windows Server lab simulating a real corporate IT environment with Active Directory, DNS, DHCP, Group Policy, File & Print Services, Storage Spaces, and Backup & Recovery.

---

## 📌 Overview

This project demonstrates the full lifecycle design, deployment, administration, and security hardening of a **Windows Server 2019 enterprise environment** using VMware Workstation.

The lab simulates the **ACME Corporation** corporate infrastructure, supporting centralized authentication, network services, file management, print services, storage, backup, and Group Policy enforcement — mirroring a real-world enterprise IT operation.

---

## 🏗️ Network Architecture

| Server | Role |
|--------|------|
| AcmePDC01 | Primary Domain Controller |
| AcmePDC02 | Secondary Domain Controller |
| AcmeWks1001 | Domain Workstation (Windows 10 Enterprise) |

**Domain:** `AD.ACME.EDU`

**Virtualization:** VMware Workstation — Windows Server 2019 + Windows 10 Enterprise clients

---

## 🛠️ Technologies Implemented

### 🔐 Identity & Access Management
- Active Directory Domain Services (AD DS)
- Domain Controller promotion and configuration
- Organizational Unit (OU) design and hierarchy
- User account and security group management
- Distribution groups and home directories

### 🌐 Network Services
- **DHCP** — Scope creation, authorization, reservations, dynamic IP assignment
- **DNS** — Forward/reverse lookup zones, host records, CNAME, MX records, name resolution testing

### 📂 File & Print Services
- Shared folder creation with NTFS permissions
- Department-level file shares
- Role-based access control (RBAC)
- User home directory automation
- Network printer deployment and security groups

### 💾 Storage Management
- Windows Storage Spaces configuration
- Virtual disk creation
- RAID implementation and volume management

### 🔄 Backup & Disaster Recovery
- Windows Server Backup configuration
- Scheduled backup jobs
- File recovery testing
- RAID failure simulation and recovery

### 🛡️ Group Policy Administration
- Password complexity and expiration policies
- Account lockout policies
- Kerberos policy configuration
- Login banners and desktop standardization
- Screen timeout enforcement
- Local account hardening
- Software deployment via GPO

---

## 📋 Lab Structure

| Lab | Topic |
|-----|-------|
| Lab 1 | Active Directory Setup & Domain Controller Promotion |
| Lab 2 | DNS & DHCP Configuration |
| Lab 3 | Organizational Units, Users & Groups |
| Lab 4 | File Services & NTFS Permissions |
| Lab 5 | Print Services & Printer Security |
| Lab 6 | Storage Spaces & RAID Configuration |
| Lab 7 | Backup & Disaster Recovery |
| Lab 8 | Group Policy Administration & Security Hardening |

---

## 🔑 Key Accomplishments

- ✅ Promoted Windows Server to Primary and Secondary Domain Controllers
- ✅ Designed and implemented a multi-OU Active Directory hierarchy
- ✅ Configured DNS with forward/reverse lookup zones and all record types
- ✅ Deployed DHCP with scopes, reservations, and failover
- ✅ Implemented departmental file shares with role-based NTFS permissions
- ✅ Configured Windows Server Backup and tested full disaster recovery
- ✅ Applied security-focused Group Policies across all OUs
- ✅ Renamed and disabled default local accounts to reduce attack surface
- ✅ Simulated RAID storage failure and successfully restored data

---

## 🧠 Skills Demonstrated

`Windows Server Administration` `Active Directory` `Group Policy` `DNS` `DHCP` `Identity & Access Management` `File Server Administration` `Storage Management` `Backup & Recovery` `Security Hardening` `VMware` `Enterprise IT Operations`

---

## 📁 Repository Contents

```
📦 Windows-server-enterprise-administration
├── 📄 README.md
├── 📋 Acme Lab 1-KHS.pdf    ← AD Setup & Domain Controller
├── 📋 Acme Lab 2-KHS.pdf    ← DNS & DHCP
├── 📋 Acme Lab 3-KHS.pdf    ← OUs, Users & Groups
├── 📋 Acme Lab 4-KHS.pdf    ← File Services & NTFS
├── 📋 Acme Lab 5-KHS.pdf    ← Print Services
├── 📋 Acme Lab 6-KHS.pdf    ← Storage Spaces & RAID
├── 📋 Acme Lab 7-KHS.pdf    ← Backup & Recovery
└── 📋 Acme Lab 8-KHS.pdf    ← Group Policy & Hardening
```

---

## 💡 Real-World Relevance

This lab directly maps to enterprise IT and SOC environments where:
- **Active Directory** is the backbone of identity and access management
- **Group Policy** enforces security baselines across all endpoints
- **DNS and DHCP** are critical infrastructure services requiring hardening
- **Backup and recovery** procedures are essential for ransomware resilience

---

## ⚠️ Disclaimer

This lab was built in a controlled VMware virtualization environment for educational and academic purposes only. All domain names, user accounts, and organizational data are fictitious.

---

## 👤 Author

**Hashan Kodippilige**  
M.S. Cybersecurity — Minnesota State University Moorhead  
📧 hashansharindu@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hashankodippilige/)  
🐙 [GitHub](https://github.com/hashan-kodippilige)
