# Cybersecurity Exam Project: ProFTPD Exploitation and MySQL Data Exfiltration

This repository contains the technical report and documentation for the **Cybersecurity** course exam (Università degli Studi di Trieste).

The project documents a multi-stage attack chain executed within an isolated sandbox environment, covering network reconnaissance, exploitation, and data exfiltration from a MySQL database, while analyzing the associated vulnerabilities and security risks.

## Project Objectives
This demo demonstrates the phases of a real-world attack based on the **MITRE ATT&CK framework**, highlighting specific security flaws:
- **Reconnaissance:** Network mapping (ARP scan and Nmap).
- **Initial Access:** Exploitation of **CVE-2015-3306** (ProFTPD `mod_copy`).
- **Post-Exploitation:** Shell stabilization (TTY upgrade) and privilege analysis (`www-data` context).
- **Data Exfiltration:** Static source code analysis (`payroll_app.php`), discovery of hardcoded credentials, and MySQL database dumping.

## Technical Report
The project report is written in Markdown and is available online via Docsify:
[View the Report Online](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/AleDena/cybersecurity-exam-report/main&homepage=home.md&sidebar=true#/?id=cybersecurity-demo-proftpd-exploitation-and-mysql-plaintext-data-exfiltration)

## Video Demo
The full video demonstration of the attack is available on YouTube:
[Watch the Video Demo](https://youtu.be/GFJoJC5dhOM)