# OSS_Audit_24BAS10090
# Open Source Audit Project

**Name:** Shreya Varma  
**Registration Number:** 24BAS10090  
**Chosen Software:** LibreOffice  

---

## Project Overview

This project presents a detailed open-source audit of LibreOffice. It explores its background, licensing model, ethical considerations, role in the Linux ecosystem, and its impact on the broader FOSS community.  

Additionally, the project includes five practical shell scripts demonstrating Linux automation and system-level operations.

---

## Scripts Included

| Script | Description |
|--------|-------------|
| `system_info.sh` | Displays system details like OS, kernel, user, and uptime |
| `package_check.sh` | Verifies LibreOffice installation and shows FOSS philosophy |
| `disk_audit.sh` | Checks directory sizes and permissions |
| `log_analyzer.sh` | Scans log files for specific keywords |
| `manifesto.sh` | Creates a personalized open-source manifesto |

---

## How to Run the Scripts

### Step 1: Make Scripts Executable
```bash
chmod +x *.sh
```

### Step 2: Execute Scripts

```bash
./system_info.sh
./package_check.sh
./disk_audit.sh
sudo ./log_analyzer.sh /var/log/dpkg.log.1 error
./manifesto.sh
```

---

## Requirements

- Linux OS (Ubuntu, Kali, Debian, Fedora, etc.)
- Bash shell (v4+)
- LibreOffice installed
- sudo privileges (for log analysis)

---

## Installation Guide

### Debian-based Systems
```bash
sudo apt update
sudo apt install libreoffice -y
chmod +x *.sh
```

### Fedora/RHEL
```bash
sudo dnf install libreoffice
chmod +x *.sh
```

---

## Project Structure

```
oss-audit-24BAS10090/
├── README.md
├── system_info.sh
├── package_check.sh
├── disk_audit.sh
├── log_analyzer.sh
└── manifesto.sh
```

---

## Submission Details

| Field | Information |
|------|-------------|
| **Student Name** | Shreya Varma |
| **Registration Number** | 24BAS10090 |
| **Course** | Open Source Software |
| **Project Title** | Open Source Audit |
| **Software Analyzed** | LibreOffice |
| **Submission Date** | March 2026 |

---
