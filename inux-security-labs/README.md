# Linux Security Labs

## Overview

This section documents my practical labs related to **Linux security, system analysis, and hardening**.

The goal of this repository is to build and document hands-on knowledge of how Linux systems work from a **security perspective**, including:

- System enumeration
- User and permission analysis
- Process and service inspection
- Network configuration analysis
- Log analysis
- Basic system hardening

The labs are conducted primarily using **Kali Linux and Debian-based environments**.

---

## Objectives

- Develop a deeper understanding of Linux system internals
- Practice security-relevant system inspection techniques
- Learn how attackers enumerate Linux systems
- Understand defensive hardening strategies
- Document commands and workflows clearly

---

## Tools and Commands Used

Common Linux tools used throughout the labs include:

### System Enumeration
- uname
- hostname
- lsb_release
- id
- whoami

### User & Permission Analysis
- ls
- stat
- find
- getfacl
- chmod
- chown

### Process & Service Analysis
- ps
- top
- htop
- systemctl

### Network Analysis
- ip
- ss
- netstat
- nmap

### Logging
- journalctl
- dmesg
- cat /var/log/auth.log

---

## Repository Structure

```
linux-security-labs/
├── enumeration
├── permissions
├── process-analysis
├── network-analysis
├── logging
├── hardening
└── lab-notes
```

---

## Methodology

Each lab follows a simple workflow:

1. Identify system information
2. Enumerate users and permissions
3. Analyze running services
4. Inspect network configuration
5. Review system logs
6. Identify potential security weaknesses
7. Document findings

---

## Legal and Ethical Position

These labs are conducted in **controlled environments and personal systems only**.

The purpose is to develop **defensive security knowledge and system administration skills**.

---

## Author

Alexander Bork  
Cybersecurity | IT Law | Compliance | OSINT
