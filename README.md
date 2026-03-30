# Open Source Audit: Apache HTTP Server

## Student Information
- **Name:** [Jayesh Dhingra]
- **Registration Number:** [24BAI10622]
- **Course:** Open Source Software
- **Software Audited:** Apache HTTP Server
- **Date:** 30 March 2026

## Project Overview
This project conducts a comprehensive audit of the Apache HTTP Server, exploring its origins, license philosophy, Linux footprint, ecosystem, and comparison with proprietary alternatives.

## Scripts Included

| Script | Purpose | Usage |
|--------|---------|-------|
| `script1_system_report.sh` | Displays system information | `./script1_system_report.sh` |
| `script2_package_inspector.sh` | Checks Apache installation | `./script2_package_inspector.sh` |
| `script3_disk_auditor.sh` | Audits directory permissions | `./script3_disk_auditor.sh` |
| `script4_log_analyzer.sh` | Analyzes log files | `./script4_log_analyzer.sh [logfile] [keyword]` |
| `script5_manifesto.sh` | Generates open source manifesto | `./script5_manifesto.sh` |

## Prerequisites
- Ubuntu/Debian Linux (or WSL)
- Apache HTTP Server installed
- Bash shell

## Installation
```bash
# Install Apache (if not installed)
sudo apt update
sudo apt install apache2 -y

# Make scripts executable
chmod +x script*.sh
How to Run the Project
Step 1: Clone the repository
git clone 
cd oss-audit-24BAI10622
