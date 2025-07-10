# DFIR-Autopsy-Analysis
Detailed forensic analysis of a Windows XP disk image using Autopsy, uncovering password cracking tools, network scanners, and suspicious executables.

# DFIR Autopsy Analysis

## 🔍 Overview
This repository contains a **digital forensic analysis report** of a Windows XP disk image (**4Dell Latitude CPi.E01**) performed using **Autopsy 4.21.0**. The objective was to identify forensic artifacts, uncover suspicious activity, and document findings as part of personal DFIR skill development.

## 🛠️ Tools Used
- Autopsy 4.21.0

## 📂 Contents

1. **DFIR Final Report (PDF)** – Technical analysis and findings.
2. **Disk Image (.E01)** – Available via external link due to GitHub file size limitations.
3. **Annex folder** – Screenshots, logs, and supporting evidence (if uploaded).

## ✅ Key Findings

- **Password cracking tools** detected (Cain & Abel, pwdump).
- **Network reconnaissance utilities** including Nmap and Netcat.
- **Suspicious executables** for enumeration and exploitation.
- **Browsing history** accessing hacking resources and exploit material.
- **USB device usage** indicating possible external data transfers.

## 📌 Recommendations

- Investigate stored credentials for potential compromise.
- Review USB device logs for data exfiltration.
- Analyze network activity to check for unauthorized access.
- Preserve all forensic evidence with proper chain of custody practices.

## 🔗 Disk Image Download

Due to GitHub storage limits, download the disk image here:

[Download 4Dell Latitude CPi.E01](YOUR-EXTERNAL-LINK-HERE)

---
## 📸 Screenshots & Analysis Highlights

### 🔍 Suspicious Executables Identified

![screely-1752110760416](https://github.com/user-attachments/assets/28ed776a-41f7-4b9f-a960-0edb0f012604)

*Autopsy displaying suspicious executables, including pwdump.exe for password dumping and STREAMFIND.EXE for detecting NTFS alternate data streams.*

---

### 🌐 Web History Analysis


![screely-1752111211254](https://github.com/user-attachments/assets/d268f7a6-7802-41e4-896a-5ba429f39a17)

*Web history artifacts showing access to hacking-related websites, supporting findings of potential exploitation activities.*

---

### 📦 Archive Files Investigation

![screely-1752111782854](https://github.com/user-attachments/assets/8024b659-5811-4d58-a4a4-0cbf9012800e)


![screely-1752111692910](https://github.com/user-attachments/assets/4c062c8f-6513-46a0-a61f-0059ede18cbb)


*Analysis of archive files to identify hidden malicious scripts or binaries.*
---
🔷 Conclusion

This forensic analysis demonstrated the systematic investigation of a Windows XP disk image using Autopsy 4.21.0, uncovering critical artifacts such as password dumping tools, network reconnaissance utilities, and suspicious web activity. The findings suggest the system was used for offensive security purposes, including potential penetration testing or unauthorized exploitation.

Through this Lab, we highlighted:

    Effective identification of system artifacts, installed programs, and suspicious files

    The importance of prefetch, registry, and web history analysis in DFIR workflows

    Structured reporting to support incident response, legal processes, and threat hunting

Key Takeaway:
🔑 A disciplined, methodical approach using open-source tools like Autopsy empowers digital forensics professionals to uncover actionable evidence efficiently and maintain the integrity of investigations.

---
### 💡 **Notes**
This analysis is shared **solely for educational and skill demonstration purposes**. All data used is from publicly available DFIR practice images.

---

### 🔗 **Contact**
For questions or collaboration, connect via [LinkedIn](https://www.linkedin.com/in/nikhil-lobo-926179191/) .
