# Hi there, I'm Adnan A 👋

<p align="left">
  <img src="https://img.shields.io/badge/Cybersecurity_Student-PSUT-0077B5?style=for-the-badge&logo=school&logoColor=white">
  <img src="https://img.shields.io/badge/CTF_Player-Competitor-FF5722?style=for-the-badge&logo=flag&logoColor=white">
  <img src="https://img.shields.io/badge/OSINT_%26_Forensics-Investigation-4CAF50?style=for-the-badge&logo=target&logoColor=white">
  <img src="https://img.shields.io/badge/Blue_Team_%26_SOC-Defensive-1E90FF?style=for-the-badge&logo=shield&logoColor=white">
  <img src="https://img.shields.io/badge/CCT_Trained-EC--Council-00A9E0?style=for-the-badge">
</p>

I'm a **Cybersecurity Bachelor's Student at Princess Sumaya University for Technology (PSUT)** and an active **CTF Player & Competitor**. 

In the CTF and security research world, I focus on unraveling complex puzzles across **Open-Source Intelligence (OSINT)**, **Git & Digital Forensics**, **Cyber Threat Intelligence (CTI)**, and **Defensive Security Operations**. I thrive on digging deep into hidden Git plumbing, unearthing deleted artifacts, tracking state-sponsored threat actors, and extracting actionable intelligence from raw data.

---

## 🚩 Featured CTF Write-Ups & Research

### 🏆 [Cyrptix CTF — OSINT & Digital Forensics Write-Ups Collection](https://github.com/Dabuynyx/Cyrptix-CTF-OSINT-write-up)
> **Event:** Cryptix CTF — Organized by **HTU Cyber Club** in collaboration with **CYS-TECH**  
> **Track:** OSINT, Git Forensics, Applied Cryptography, Web Archive Forensics, Cyber Threat Intelligence  
> **Status:** 5 / 5 Challenges Solved (100% Clear)

A complete, production-grade repository documenting step-by-step methodologies, reproducible CLI pipelines, custom extraction scripts, visual flowcharts, and primary disclosures:

| Challenge | Focus & Techniques | Solved Flag |
| :--- | :--- | :--- |
| **[The Ghost in the Blocks](https://github.com/Dabuynyx/osint-writeup-cytech-the-ghost-in-the-blocks)** | Threat actor footprinting, commit diff digging, scrubbed configuration recovery, Base64 | `CTF{cryptix}` |
| **[Bangladesh Bank Cyber Heist](https://github.com/Dabuynyx/osint-writeup-cytech-bangladesh-bank-cyber-heist)** | 2016 Lazarus Group SWIFT attack, printer DLL sabotage, DOJ court docket day-count verification | `Cryptix{fandation_Jupiter_ChosunExpoJointVenture_90}` |
| **[Old Friends](https://github.com/Dabuynyx/osint-writeup-cytech-old-friends)** | Web archive snapshot DOM forensics, Base64 image payload carving, EXIF GPS coordinate math | `Cryptix{stonehenge}` |
| **[Behind the Shroud](https://github.com/Dabuynyx/osint-writeup-cytech-behind-the-shroud)** | Hamza Bendelladj (Bx1) case facts vs viral myth, SpyEye Trojan, Darkode takedown (Op Shrouded Horizon) | `Cryptix{OperationShroudedHorizon_12_M1rr0r}` |
| **[Ghost in the Release](https://github.com/Dabuynyx/osint-writeup-cytech-ghost-in-the-release)** | Git plumbing refs (`refs/pull`, `refs/notes`), dangling commits (`git fsck`), OpenSSL PBKDF2/AES-256-CBC, Gist OSINT | `Cryptix{v4ult_unl0ck3d_st4g3_tw0_n0t3s_0s1nt_g1st_w1ns}` |

---

## 🔑 Security & Software Projects

### 1. 🏢 [QAMRA Fit Life – Secure Web Platform & Access Control](https://github.com/Dabuynyx/QAMRA)
A secure web platform architected with strict defensive programming principles:
* **Privilege Separation:** Multi-tier authentication distinguishing Customer, Administrator, and Root roles.
* **Access Control & Lifecycle:** Role-Based Access Control (RBAC), reauthentication for sensitive actions, account state enforcement (Active, Banned, Frozen).
* **Database Hardening:** PDO prepared statements, parameterized queries preventing SQL injection, transaction handling with row-level locks (`FOR UPDATE`).
* **Cryptographic Best Practices:** Modern password hashing via `password_hash()` (Argon2/bcrypt) and safe session token lifecycles.

### 2. 🛡️ [SecureLog Analyzer](https://github.com/Dabuynyx/SecureLog)
A Python security tool automating the parsing and triage of server log files for suspicious intrusion activity:
* **Detection Capabilities:** Identifies brute-force authentication spikes, known attack patterns, and Indicators of Compromise (IOCs).
* **SIEM Principles:** Implements rule-based parsing and alerting aligned with Blue Team security operations workflows.

### 3. 🔐 [Python Password Manager](https://github.com/Dabuynyx/Password-Manager)
A standalone credential vault implemented in Python with local cryptographic protection and safe memory/file handling.

---

## 🎯 My CTF & Security Toolkit

<p align="left">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git_Forensics-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img alt="Wireshark" src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white">
  <img alt="Nmap" src="https://img.shields.io/badge/Nmap-E44C30?style=for-the-badge">
  <img alt="Splunk" src="https://img.shields.io/badge/SIEM_&_Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white">
  <img alt="Bash" src="https://img.shields.io/badge/Bash_Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white">
</p>

### 🔍 CTF & Investigation Domains
* **OSINT & Footprinting:** Deep open-source searching, username pivoting, public repository audits, GitHub Gist tracking, domain/IP intelligence.
* **Digital & Web Forensics:** Web archive timeline analysis, EXIF metadata extraction, coordinate trigonometry, HTTP payload recovery.
* **Git Plumbing Forensics:** Detached ref exploration, `git notes` namespaces, unreachable & dangling commit carving (`git fsck`), commit patch diff auditing.
* **Applied Cryptography:** Multi-stage OpenSSL pipelines (PBKDF2, AES-256-CBC, HMAC, SHA-256), Base64 block alignment, encoded payload reverse engineering.
* **Cyber Threat Intelligence (CTI):** Threat group profiling (Lazarus Group / APT38, cybercrime forums like Darkode), judicial docket tracking (DOJ, CourtListener), IOC correlation.

---

## 🎓 Training & Certifications

* **CCT Trained:** Certified Cybersecurity Technician (EC-Council)
* **TryHackMe:** Completed **SOC Level 1 Path** (Security Monitoring, Event Analysis, Threat Detection, Network Defense)
* **Academic:** Cybersecurity Bachelor's Program at **Princess Sumaya University for Technology (PSUT)**

---

## 🎯 What I'm Looking For

I'm actively participating in CTF competitions, security challenges, and seeking collaborative opportunities in:
> **CTF Teams & Competitions** | **Digital Forensics & Incident Response (DFIR)** | **Threat Intelligence & Hunting** | **SOC / Blue Team Analysis** | **Security Engineering**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Dabuynyx&show_icons=true&theme=gruvbox&rank_icon=github" alt="Adnan's GitHub Stats" />
</p>

---

## 📫 Connect With Me

* **LinkedIn:** [linkedin.com/in/adnan-al-hmoud](https://www.linkedin.com/in/adnan-al-hmoud/)
* **GitHub:** [@Dabuynyx](https://github.com/Dabuynyx)
