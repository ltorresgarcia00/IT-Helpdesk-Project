# 🐧 Ubuntu VM Setup (UTM)
## Foundation for IT Help Desk & Active Directory Lab

This section documents the initial configuration of the **Ubuntu Linux virtual machine** used as the infrastructure foundation for the IT Help Desk + Active Directory lab environment.

The Ubuntu VM hosts:

- osTicket (Help Desk system)
- LAMP stack services
- Supporting network services
- Ticket documentation platform

The VM runs in **UTM (QEMU ARM64)** on an Apple Silicon Mac and integrates into a hybrid lab alongside:

- Windows Server (Active Directory Domain Controller)
- Windows 11 domain-joined client

---

## 🛠️ Environment Details

### 💻 Host System
- macOS (Apple Silicon – M3)
- UTM Virtualization (QEMU ARM64)

### 🖥 Guest System
- Ubuntu 25.10 (ARM64)
- Network Mode: Shared (NAT)
- Memory Allocation: 6 GB RAM
- Disk Allocation: ~20 GB virtual disk
- CPU: 4 virtual cores (recommended)

---

## 🔄 Initial System Update & Hardening

After installation, the system was fully updated to ensure all security patches and packages were current.

```bash
sudo apt update && sudo apt upgrade -y
