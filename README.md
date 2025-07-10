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

<img src="screenshots/image5_executables_analysis.png" width="800"/>

*Autopsy displaying suspicious executables, including pwdump.exe for password dumping and STREAMFIND.EXE for detecting NTFS alternate data streams.*

---

### 🌐 Web History Analysis

<img src="screenshots/image3_web_history_analysis.png" width="800"/>

*Web history artifacts showing access to hacking-related websites, supporting findings of potential exploitation activities.*

---

### 📦 Archive Files Investigation

<img src="screenshots/image9_archive_files_analysis.png" width="800"/>

*Analysis of archive files to identify hidden malicious scripts or binaries.*


---
### 💡 **Notes**
This analysis is shared **solely for educational and skill demonstration purposes**. All data used is from publicly available DFIR practice images.

---

### 🔗 **Contact**
For questions or collaboration, connect via [LinkedIn](https://www.linkedin.com/in/nikhil-lobo-926179191/) .
