# 🫐 BLUEBERRY - Code Name: Blueberry
### Advanced Framework for Red & Blue Team Operations | Ethical Penetration Testing | Cryptography | Digital Forensics

![Project Status](https://img.shields.io/badge/Status-Under%20Active%20Development-green?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-Ethical%20Hacking-red?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-Red%20%26%20Blue-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-v1.0.0-orange?style=for-the-badge)

**Code Name BLUEBERRY** - A unified framework that blends the offensive power of Red Team with the defensive resilience of Blue Team, secured by Cryptography and investigated by Digital Forensics.


---

## 📑 Table of Contents
- [About The Project](#-about-the-project)
- [Why Blueberry?](#-why-blueberry)
- [Core Modules](#-core-modules-detailed)
- [Architecture](#-architecture)
STATUS: UNDER ACTIVE DEVELOPMENT
  - [Installation](#-installation)
- [Detailed Usage](#-detailed-usage)
- [Methodology](#-methodology)
- [Cryptography Implementation](#-cryptography-implementation)
- [Digital Forensics Workflow](#-digital-forensics-workflow)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Lab Setup](#-lab-setup)
- [Case Studies](#-case-studies)
- [Legal & Ethical Disclaimer](#-legal--ethical-disclaimer)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License & Contact](#-license--contact)

---

## 📖 About The Project

*BLUEBERRY* is a comprehensive, open-source research and training framework designed to simulate real-world cyber attack and defense scenarios. This project integrates four critical domains of modern cybersecurity into a single operational platform.
This framework is built for:
- Cybersecurity students and researchers
- Red Team / Blue Team / Purple Team professionals
- SOC Analysts and Incident Responders
- CTF Players and Bug Bounty Hunters
- Digital Forensics Investigators

The name *BLUEBERRY* signifies the fusion of RED (Offense) and BLUE (Defense) - creating a purple-team mindset that is sweet on the outside but has deep, complex layers inside, just like the fruit.

### Project Goals:
1. To provide a hands-on lab for learning end-to-end attack lifecycles.
2. To teach how to detect, respond, and harden systems against those attacks.
3. To implement secure communication using modern cryptography.
4. To conduct post-incident forensic analysis to find root cause and evidence
5. *D) Hardening & Remediation:*
- CIS Benchmark checks
- Firewall rule automation
- Patch management checklist

### 3. ⚪ ETHICAL PENETRATION TESTING
A structured, professional pentesting workflow.

*Methodology Followed: PTES & OWASP Top 10 2023*
1.  *Pre-Engagement:* Scope definition, Rules of Engagement (RoE), NDA template included
2.  *Intelligence Gathering:* OSINT and technical information collection
3.  *Threat Modeling:* Identifying assets and attack vectors
4.  *Vulnerability Analysis:* Manual + Automated scanning, false positive validation
5.  *Exploitation:* Gaining access with proof-of-concept, maintaining ethical boundaries
6.  *Post-Exploitation:* Determining impact and data sensitivity
7.  *Reporting:* Executive summary + Technical details + Remediation steps + CVSS scoring

Includes a professional penetration testing report template in /templates/report_template.md
### 4. 🔐 CRYPTOGRAPHY
Ensures confidentiality, integrity, and authenticity of all operations and communications.

*A) Symmetric Encryption:*
- Algorithm: AES-256-GCM (Authenticated Encryption)
- Use Case: Encrypting exfiltrated data (simulation), encrypting reports, secure file storage
- Key Management: Secure key generation and exchange simulation

*B) Asymmetric Encryption:*
- Algorithm: RSA-2048 / RSA-4096, ECC
- Use Case: Secure key exchange, Digital Signatures
- Implementation: Public/Private key pair generation, certificate simulation

*C) Hashing & Integrity:*
- Algorithms: SHA-256, SHA-3, bcrypt for password hashing
- Use Case: File integrity monitoring (Blue Team), Password cracking simulation (Red Team - with wordlists), Evidence integrity in forensics
- *D) Steganography & Obfuscation:*
- Hiding data inside images (LSB method)
- Base64, Hex encoding for payload obfuscation (educational purpose)

### 5. 🔍 DIGITAL FORENSICS (DFIR)
Post-incident investigation to answer: What happened? When? How? Who?

*A) Disk Forensics:*
- Imaging: Creating forensic images (DD, E01 concept)
- File System Analysis: NTFS, EXT4 analysis, recovering deleted files
- Timeline Analysis: Creating super timeline with Plaso/log2timeline
- Artifact Analysis: Registry hives, Prefetch, Browser history, LNK files

*B) Memory Forensics:*
- Memory Acquisition (using dump simulation)
- Analysis with Volatility Framework concepts: Process listing (pslist), Network connections (netscan), Malicious code injection (malfind)
- Credential extraction from memory

*C) Network Forensics:*
- PCAP analysis with Wireshark concepts
- Reconstructing TCP streams, extracting files from PCAP
- Detecting C2 (Command & Control) communication
- *D) Chain of Custody:*
- Evidence hashing (SHA-256) immediately after collection
- Chain of custody log template included in /forensics/coc_template.txt
- Forensically sound handling procedures

---

## 🏗️ Architecture
