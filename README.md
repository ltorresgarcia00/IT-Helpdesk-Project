# IT Help Desk & Active Directory Project (In Progress)
## 🎫 osTicket + Active Directory (Hybrid IT Support Lab)

---

🎥 Project Walkthrough (3-Minute Demo)
[Watch Here] (Coming Soon)


## 📌 Overview

This project simulates a real-world **enterprise IT Help Desk environment** using:

- **osTicket (Ubuntu Linux)**
- **Windows Server Active Directory**
- **Windows 11 Domain-Joined Client**
- **UTM Virtualization (Apple Silicon)**

The lab demonstrates how IT support teams receive, triage, escalate, and resolve technical issues involving:

- Active Directory user management
- Account lockouts and password resets
- Group-based access control
- Cloud identity troubleshooting
- Endpoint and network issues

This mirrors real Tier 1 / Tier 2 support workflows used in corporate environments.

---

## 🛠️ Environment

### 💻 Host System
- macOS (Apple Silicon – M3)
- UTM (QEMU ARM64 virtualization)

### 🖥 Virtual Machines

**1️⃣ Windows Server (Domain Controller)**
- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management

**2️⃣ Windows 11 Client**
- Domain-joined device
- Simulated end-user workstation

**3️⃣ Ubuntu Linux Server**
- Apache Web Server
- PHP
- MariaDB
- osTicket (latest version)

### ⚙️ Resource Allocation
- Windows Server: 4–6 GB RAM
- Windows Client: 4 GB RAM
- Ubuntu: 4–6 GB RAM
- Disk: ~20–60 GB per VM
- Network: NAT (internal lab network)

---

## 🧠 Active Directory Configuration

- Installed and configured **Active Directory Domain Services**
- Created:
  - Users
  - Security Groups
  - Organizational Units (OUs)
- Configured **Group Policy Objects (GPOs)**
- Simulated:
  - Account lockouts
  - Password resets
  - Group membership changes
  - Domain join troubleshooting
  - RDP access permissions
- Practiced **least privilege and RBAC principles**

---

## 🎫 Ticketing System (osTicket)

Deployed osTicket to simulate structured IT support workflows.

### Configurations
- Created departments (IT Support, Security)
- Defined agent roles and permissions
- Configured ticket priorities and SLAs
- Customized email templates and auto-responses
- Implemented escalation workflows

---

## 🧪 Example Tickets Handled

### 🔐 Active Directory Issues
- User account locked out
- Password reset requests
- Group access provisioning
- OU reassignment
- GPO-related login issues

### ☁️ Identity & Access Issues
- MFA login failures
- Cloud identity access troubleshooting
- Role-based access control adjustments

### 🌐 Network & System Issues
- DNS resolution failures
- Slow system performance
- Application crashes
- Network connectivity issues

### 🛡 Security-Related Tickets
- Suspicious login attempt
- Account compromise investigation
- Privilege escalation request review

Each ticket included:
- Detailed issue description
- Step-by-step troubleshooting
- Resolution documentation
- Escalation notes (if applicable)
- Closure summary

---

## 🔑 Skills Demonstrated

### 🖥 Systems Administration
- Windows Server configuration
- Active Directory management
- GPO implementation
- Linux server administration

### 🎫 Help Desk Operations
- Ticket lifecycle management
- SLA awareness
- Tier 1 / Tier 2 escalation processes
- Technical documentation best practices

### 🔐 Identity & Access Management
- User provisioning and deprovisioning
- Group-based access control
- Account lifecycle management
- Authentication troubleshooting

### 🌐 Networking
- DNS troubleshooting
- Domain authentication flow
- RDP and remote access configuration

### 🛡 Security Concepts
- Least privilege
- Role-based access control (RBAC)
- Account lockout policies
- Basic incident triage

---

## 📸 Screenshots Included

- Windows Server AD configuration
- Users & Groups management
- Group Policy setup
- Domain-joined Windows 11 system
- Ubuntu system overview
- osTicket dashboard
- Sample open/in-progress/resolved tickets
- SLA and department configuration

---

## 🎯 Career Relevance

This lab mirrors real-world workflows used in roles such as:

- Help Desk Technician
- IT Support Specialist
- Service Desk Analyst
- Desktop Support Technician
- Junior Systems Administrator
- SOC Analyst (entry-level)

It demonstrates hands-on experience across:

- Active Directory environments
- Ticket-based IT operations
- Hybrid infrastructure troubleshooting
- Identity and access management

---

## 🚀 Key Takeaway

This project bridges:

Active Directory Administration  
+ Help Desk Operations  
+ Linux Server Deployment  
+ Security Fundamentals  

Providing practical experience aligned with modern IT support and early-career cybersecurity roles.
