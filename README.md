<div align="center">

# I'm Pooja Noochila

#### SOC Analyst | Blue Team | DFIR | MCA Graduate

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/pooja-noochila)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:noochilapooja@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-%23212C42.svg?logo=tryhackme&logoColor=white)](https://tryhackme.com/p/pooja974)
[![CyberDefenders](https://img.shields.io/badge/CyberDefenders-%230072C6.svg?logoColor=white)](https://cyberdefenders.org/p/pooja0707/)

</div>

---

## About Me

I'm a cybersecurity practitioner focused on Blue Team operations, including threat detection, incident investigation, SIEM, digital forensics, phishing analysis, and network forensics. I build hands-on SOC and DFIR projects through TryHackMe, CyberDefenders, and industry workshops.

Currently open to **SOC Analyst L1** and **Digital Forensics** roles and blue team internships.

---

## Technical Skills

<div align="center">
  
**SIEM & Security Monitoring**

![Splunk](https://img.shields.io/badge/Splunk-black?style=for-the-badge)
![Wazuh](https://img.shields.io/badge/Wazuh-black?style=for-the-badge)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-black?style=for-the-badge)
![Zeek](https://img.shields.io/badge/Zeek-black?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-black?style=for-the-badge)
![Nmap](https://img.shields.io/badge/Nmap-black?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-black?style=for-the-badge)
![VirusTotal](https://img.shields.io/badge/VirusTotal-black?style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-black?style=for-the-badge)

**Digital Forensics**

![Autopsy](https://img.shields.io/badge/Autopsy-black?style=for-the-badge)
![FTK Imager](https://img.shields.io/badge/FTK%20Imager-black?style=for-the-badge)
![Magnet Acquire](https://img.shields.io/badge/Magnet%20Acquire-black?style=for-the-badge)
![HxD](https://img.shields.io/badge/HxD%20Hex%20Editor-black?style=for-the-badge)

**Cryptography & PKI**

![PKI](https://img.shields.io/badge/PKI-black?style=for-the-badge)
![RSA](https://img.shields.io/badge/RSA-black?style=for-the-badge)
![SHA](https://img.shields.io/badge/SHA%20Hashing-black?style=for-the-badge)

**Languages & Scripting**

![Python](https://img.shields.io/badge/python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**Platforms & Infrastructure**

![Linux](https://img.shields.io/badge/linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![WSL](https://img.shields.io/badge/WSL%20%2F%20Ubuntu-black?style=for-the-badge&logo=ubuntu&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## Projects

<details><summary><b> Phishing Investigation Case Study</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Conduct a structured phishing email investigation using header analysis, URL inspection, and sandbox detonation |
| Tools | Email header analyzers · URLScan.io · VirusTotal · Any.run · Wireshark |
| Detection Logic | SPF/DKIM/DMARC validation failures, suspicious sender patterns, C2 callback detection |
| MITRE ATT&CK Mapping | T1566.001 (Spearphishing Attachment), T1566.002 (Spearphishing Link), T1204 (User Execution) |
| Security Impact | Documented a complete phishing investigation playbook applicable to real SOC triage workflows |
| Repository | https://github.com/poojanoochila/phishing-incident-analysis |

</details>

<details><summary><b> EDR Threat Detection & Response</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Simulate an endpoint compromise and investigate it end-to-end using Microsoft Defender for Endpoint |
| Tools | Microsoft Defender for Endpoint · MITRE ATT&CK |
| Detection Logic | Investigated malicious process behavior, extracted IOCs including suspicious file paths and lateral network connections, and correlated each stage of the attack chain against MITRE ATT&CK |
| Security Impact | Produced a formal SOC-style incident report covering attack timeline, containment actions taken, and recommended remediation steps |
| Repository | https://github.com/poojanoochila/endpoint-malware-detection-response |

</details>

<details><summary><b> CyberOps — AI-Powered SOC Analyst Training Simulator</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Build an interactive training platform that simulates SOC alert triage scenarios using a live LLM backend |
| Stack | FastAPI · MongoDB (Motor) · Groq LLaMA 3.3 70B · React · JWT Auth |
| Key Features | Role-based login, scenario randomisation, session logging for review |
| Security Impact | Trainees investigate realistic synthetic alerts through guided prompts and receive AI-generated feedback on triage decisions without requiring access to a live SIEM |
| Repository | https://github.com/poojanoochila/cyberops-soc-analyst-training-platform |

</details>

<details><summary><b> SIEM Log Analysis Dashboard</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Build a full-stack SIEM-style dashboard to ingest, analyze, and visualize security logs for SOC investigation workflows |
| Stack | React · Python · MongoDB · VirusTotal API · MITRE ATT&CK |
| Detection Logic | Parses and correlates security events, enriches indicators with VirusTotal reputation data, and maps findings to MITRE ATT&CK tactics and techniques |
| Security Impact | Demonstrates practical threat detection, event enrichment, and incident analysis concepts in a simplified SIEM environment |
| Repository | https://github.com/poojanoochila/soc-dashboard |

</details>

<details><summary><b> Login Anomaly Detection System</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Build an ML-powered detection system that identifies suspicious login behaviour and surfaces alerts through a web dashboard |
| Stack | Python · Scikit-learn · Pandas · NumPy · Flask · Matplotlib · Seaborn |
| Detection Logic | Random Forest classifier trained on login event features with preprocessing, model evaluation, and real-time anomaly scoring |
| Key Features | Secure authentication, admin dashboard, password hashing, session management, structured audit logging |
| Repository | https://github.com/poojanoochila/login-anomaly-detection |

</details>

<details><summary><b> Secure Password Strength Analyzer</b></summary><br/>

| Attribute | Details |
|---|---|
| Objective | Evaluate password strength using entropy calculation and pattern analysis with real-time user feedback |
| Stack | Python · Flask · HTML/CSS/JS |
| Detection Logic | Entropy scoring and pattern detection including keyboard walks, common substitutions, and dictionary patterns |
| Key Features | Entropy-based scoring, pattern detection, real-time policy feedback |
| Repository | https://github.com/poojanoochila/Password-Strength-Analyzer |

</details>

---

## Hands-On Labs

###  TryHackMe
Blue team learning path focused on SOC operations, SIEM detection, and incident response. Completed rooms covering Splunk, Wazuh, Microsoft Sentinel, network analysis, and threat hunting workflows.

→ | https://github.com/poojanoochila/tryhackme-challenges |

###  CyberDefenders
Blue team challenge platform — investigations across forensics, network traffic analysis, malware triage, and endpoint detection scenarios. Each challenge writeup includes methodology, tool usage, and key findings.

→ | https://github.com/poojanoochila/cyberdefenders-challeges |

---

## Experience

**Web Development Intern — The Web People** *(April 2026 – June 2026)*
Contributed to frontend development with a focus on secure coding practices: input validation, secure rendering, authentication handling, and minimising data exposure risks in client-server interactions. Applied OWASP principles throughout the development lifecycle and maintained documentation standards across cross-functional sprint deliverables.

---

## Activities

| | |
|---|---|
|  Cybersecurity & Digital Forensics Workshop | Industry-led hands-on training covering disk imaging with FTK Imager and Magnet Acquire, artifact analysis with Autopsy and HxD, and applied cryptography including PKI, RSA, and SHA hashing |
|  CyberPeace First Responders | Incident response awareness training — digital first responder protocols |
|  Ethical Hacking Workshop | Delivered a practical session covering Nmap, Wireshark, and VirusTotal for a student audience |
|  picoCTF | Forensics and network security challenge track |

---

## GitHub Activity

<div align="center">


<img src="https://streak-stats.demolab.com/?user=poojanoochila&theme=tokyonight&background=0d0d1a&border=6d28d9&ring=a855f7&fire=7c3aed&currStreakNum=e2e8f0&currStreakLabel=a855f7&sideNums=e2e8f0&sideLabels=a855f7&dates=94a3b8" width="49%"/>

</div>
 
---

<div align="center">
<i>Detect. Investigate. Respond. Repeat.</i>
</div>
