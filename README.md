# Enterprise Active Directory Administration Lab

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
