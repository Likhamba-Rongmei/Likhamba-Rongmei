# Likhamba Rongmei
**Developer with a security background** · CompTIA Security+ · KIIT B.Tech CSE '27
`Full-Stack Web` · `Java & DSA` · `Application Security` · `Cloud Security`

---

## About

I build web applications, and I care about how they break.

I started out in security: SOC labs, cloud attack simulation and web app pentesting. That taught me how real systems get attacked. Now I'm focused on building them: full-stack web development and DSA in Java. The goal is to be a developer who writes secure software from the start, not one who patches it afterwards.

---

## Projects

- **[ARGUS](https://github.com/Likhamba-Rongmei/ARGUS)**: Full-stack document fraud detection platform (React + FastAPI). Runs forensic analysis (error level analysis, JPEG ghost, noise, metadata, PDF structure, timestamps) and registry verification in parallel on invoices, bank statements and land records, then merges both into a four-state verdict. An LLM extracts structured claims from OCR text, and a React dashboard renders a D3 force-directed evidence graph.

- **[Modern Web Stack Security Labs](https://github.com/Likhamba-Rongmei/modern-web-stack-security-labs)**: Pentest-style case studies across MERN, Next.js, Django and LAMP. Covers prototype pollution to admin in Express, CVE-2025-29927 (Next.js middleware auth bypass, CVSS 9.1), CVE-2021-35042 (Django SQL injection via `ORDER BY`, CVSS 9.8) and CVE-2021-41773 (Apache path traversal to RCE, CVSS 9.8). Each write-up covers fingerprinting, the exploit chain, impact and remediation.

- **[Deception & Log Integrity](https://github.com/Likhamba-Rongmei/deception-log-integrity)**: A Flask honeypot (decoy admin portal with a live alert dashboard and brute-force detection) paired with a tamper-evident logger that hash-chains entries with SHA-256 and pinpoints edited, deleted or reordered records.

- **[AWS Cloud SOC Lab](https://github.com/Likhamba-Rongmei/AWS-Cloud-SOC-Lab-Attack-Simulation-Detection)**: Simulated IAM privilege escalation (T1098), S3 exposure (T1530) and EC2 persistence (T1078) on a live AWS account. Rebuilt each attack timeline from raw CloudTrail logs and handled containment and remediation without managed detection services.

- **[Wazuh SIEM Implementation](https://github.com/Likhamba-Rongmei/Wazuh-SIEM-Implementation)**: Multi-host SOC lab (Ubuntu SIEM server, Windows 11 endpoint, macOS analyst station). Extended the agent config to ingest Windows Defender logs and validated brute-force and malware detections end to end.

---

## Research

**BRIDGE: An Audited Cross-Dataset Benchmark for IoT Intrusion Detection**
*Second author (of 7) · In revision at Springer Journal of Network and Systems Management*

BRIDGE unifies four public intrusion datasets, produced by three different feature-extraction toolchains, under one 46-feature schema. It first audits them for defects (up to 48.4% duplicate records, broken or missing labels). Under a leakage-controlled leave-one-dataset-out protocol, it shows that no evaluated model transfers across datasets beyond a trivial baseline, so cross-dataset IoT intrusion detection remains an open problem. My role: investigation, visualisation, and review and editing of the manuscript.

[Code & benchmark](https://github.com/Ammar-ss/TCH-Net) · [arXiv (earlier version)](https://arxiv.org/abs/2604.11324)

---

## Currently

- Practising DSA in Java
- Learning the modern web stack (Node.js next)
- TryHackMe Jr Penetration Tester path, top 5% globally

---

## Stack

| Area | Tools |
|---|---|
| Languages | Java, Python, JavaScript, C, SQL, Bash |
| Web | React, FastAPI, Flask, REST APIs, HTML/CSS, D3.js |
| Cloud & Tools | AWS (IAM, EC2, S3, VPC, CloudTrail), Git, Linux |
| Security | OWASP Top 10, Burp Suite, Wazuh, Wireshark, Nmap, Metasploit, MITRE ATT&CK |

---

## Certifications

**CompTIA Security+ (SY0-701)** · Valid Jan 2026 – Jan 2029 · [Verify on Credly](https://www.credly.com/badges/4d6f6fe6-6885-4372-afb8-be4be5df92d6/public_url)

---

## Presence

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_5%25-212C42?style=flat-square&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/Hackermaan)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Likhamba-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/likhamba-rongmei)
[![Portfolio](https://img.shields.io/badge/Portfolio-likhamba--rongmei.github.io-black?style=flat-square)](https://likhamba-rongmei.github.io)
[![Email](https://img.shields.io/badge/Email-likhambarong%40gmail.com-grey?style=flat-square&logo=gmail)](mailto:likhambarong@gmail.com)
