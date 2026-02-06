🛡️ Sentinel-Advanced-SecOps
An Advanced Cybersecurity Framework for Automated Threat Hunting, System Hardening, and Incident Response.
🚀 Projects Overview
This repository is a modular collection of 8 high-performance security tools built with Python. Each tool is designed to handle a specific stage of the Cyber Kill Chain.

1. Credential Leak Scanner
Description: Scans local environments and configuration files for exposed secrets.

Key Features: Detects hardcoded API keys, passwords, and sensitive environment variables to prevent identity theft.

2. Incident Response Playbook Automator
Description: A "Trigger-Action" engine for rapid threat containment.

Key Features: Executes automated mitigation steps like network isolation and process termination the moment an attack is confirmed.

3. Log-Based Intrusion Detector (L-IDS)
Description: A SIEM-lite correlation engine for system logs.

Key Features: Correlates events from multiple log sources (Auth + Web) to detect multi-stage attacks like Brute-force + Path Traversal.

4. Malware Hash Checker
Description: A forensic utility for file fingerprinting.

Key Features: Generates SHA-256 hashes for suspicious files and compares them against known malware databases for instant detection.

5. Ransomware Behavior Detector (Watchdog)
Description: A proactive filesystem monitor to stop encryption attacks.

Key Features: Detects abnormal file-renaming patterns and rapid encryption activities using the watchdog library.

6. Security Alert Automation
Description: A centralized notification hub for security events.

Key Features: Sends real-time alerts via Email or Telegram whenever a tool in the suite detects a critical threat.

7. Security Audit & Hardening Tool
Description: A compliance-focused script for system fortification.

Key Features: Audits system settings against security checklists and provides one-click remediation (Hardening) for SSH, Firewalls, and Permissions.

8. Threat Intelligence Feed Collector
Description: An OSINT tool to stay ahead of emerging threats.

Key Features: Automatically pulls the latest Indicators of Compromise (IOCs) and malicious IPs from global threat intelligence APIs.

📂 Project Structure
Each project is organized into its own directory for modularity:

Plaintext
/Sentinel-Advanced-SecOps
├── 01_Credential_Scanner/     # Identity & Access Audit
├── 02_IR_Playbook_Automator/  # Automated Containment
├── 03_Log_IDS/                # Intrusion Detection & Correlation
├── 04_Malware_Hash_Checker/   # File Integrity & Fingerprinting
├── 05_Ransomware_Watchdog/    # Behavioral Defense
├── 06_Security_Alert_Auto/    # Centralized Alerting
├── 07_Security_Audit_Tool/    # Compliance & Hardening
└── 08_Threat_Intel_Feed/      # OSINT & Global Intelligence
🛠️ Tech Stack
Language: Python 3.8+
## ⚖️ License & Legal Information

This project is primarily licensed under the **MIT License**, with specific modules covered under **Apache 2.0** and **GPL v3**.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-red.svg)](./LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)

### Key Permissions:
- ✅ **Commercial Use:** You can use this code for business purposes.
- ✅ **Modification:** You can change the code however you like.
- ✅ **Distribution:** You can share the code with others.
- ✅ **Private Use:** You can use it privately.

### Conditions:
- ⚠️ **Notice:** You must include the original copyright and license notice in any copy of the software/source code.

### Warranty:
- 🛡️ **No Warranty:** The software is provided "as is", without any warranty of any kind. The author is not liable for any claims or damages.

**For more details, view the [Full LICENSE File](./LICENSE)**


Libraries: hashlib, watchdog, requests, psutil, subprocess, smtplib

OS: Linux (Ubuntu/Debian/Kali) & Windows (Admin/Root access required)

👨‍💻 Author
Anuj Sharma Security Automation Enthusiast | IT Automation Specialist | Python for SecOps
