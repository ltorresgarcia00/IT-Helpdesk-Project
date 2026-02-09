# IT Help Desk Ticketing Lab
## 🎫 osTicket Help Desk System (Ubuntu on UTM)

---

### 📌 Overview
This project simulates a real-world **IT Help Desk ticketing system** using **osTicket** deployed on **Ubuntu Linux** running in **UTM (QEMU)** on an Apple Silicon Mac.

The lab focuses on hands-on experience with:
- Help desk ticket workflows
- Linux-based system administration
- Web application deployment
- Tier 1 / Tier 2 IT support processes

This project demonstrates how support teams receive, triage, escalate, and resolve technical issues using a centralized ticketing platform.

---

### 🛠️ Environment
- **Host OS:** macOS (Apple Silicon – M3)
- **Virtualization:** UTM (QEMU ARM64)
- **Guest OS:** Ubuntu Linux
- **Web Stack:** Apache, PHP, MariaDB (LAMP)
- **Ticketing System:** osTicket (latest version)
- **Memory:** 6 GB RAM
- **Disk:** ~20 GB virtual disk
- **Network:** Shared (NAT)

---

### 🎫 Ticketing System Configuration
- Configured **departments** (IT Support, Security)
- Defined **roles** and **agent permissions**
- Implemented **ticket priorities** and **SLAs**
- Customized **email templates** and responses
- Simulated real-world support workflows

---

### 🧪 Example Tickets Handled
- Password reset and account lockout
- MFA and login access issues
- Network connectivity and DNS problems
- Slow system performance
- Security-related incident escalation

Each ticket includes:
- Issue description
- Troubleshooting steps
- Resolution notes
- Closure documentation

---

### 🔑 Skills Demonstrated
- Linux system administration
- LAMP stack installation and configuration
- Help desk ticket lifecycle management
- Technical documentation and escalation
- Realistic Tier 1 / Tier 2 IT support workflows
- Troubleshooting across OS, network, and access layers

---

### 📸 Screenshots Included
- Ubuntu system overview
- osTicket installation and setup
- Admin dashboard and configuration
- Sample tickets (open, in-progress, resolved)
- SLA and department configuration

---


## Ubuntu Initial Setup

Updated the system packages to ensure the VM was fully patched before installing services.

```bash
sudo apt update && sudo apt upgrade -y

### 🎯 Why This Matters
This lab mirrors tools and workflows used in entry-level IT roles such as:
- Help Desk Technician
- IT Support Specialist
- Service Desk Analyst

It demonstrates practical experience with ticket-based support systems and Linux-hosted IT infrastructure.
