# Linux Commands and Shell Scripting
Hands on experience in using Linux commands and shell scripting for file handling, batch operation, and workflow automation.

<p id="PySpark_Certificate" align="center">

<img src="images/kesari.rishi_ShellScriotingCertificate.png"  width="1000"  height="800">
    
</p>

## Overview

This repository demonstrates foundational Linux command line and Bash scripting skills applied to a real-world automation scenario.

The core project implements an automated backup system that identifies files modified within the last 24 hours, archives them, and schedules execution using cron.

---

## Business Scenario

A company requires daily backups of sensitive files updated within the last 24 hours. Manual execution introduces:

- Human error
- Security risks
- Operational inefficiency

This project automates the process using Bash scripting and system scheduling.

---

## Core Project: Automated Backup Script

The script:

- Accepts source and destination directories as arguments
- Computes Unix timestamps for time comparison
- Identifies files modified within the last 24 hours
- Archives and compresses them using tar
- Supports scheduling via cron
- Can be installed system-wide in `/usr/local/bin`

---

## Technologies Used

- Linux CLI
- Bash
- Unix timestamps
- Arrays
- File permissions
- tar
- Cron scheduling

---

## How to Run

Make executable:

```bash
chmod +x backup.sh
