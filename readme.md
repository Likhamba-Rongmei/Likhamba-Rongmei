# Likhamba Rongmei
**CSE undergrad with a security background, moving into full-stack development** · CompTIA Security+ · KIIT B.Tech CSE '27
`Security Operations` · `Cloud Security` · `Java & DSA` · `MERN (learning)`

---

## About

My background is in security: SIEM deployment, cloud attack simulation and incident response. That taught me how real systems get attacked and how to investigate when they do.

Now I'm focused on building them. I'm practising DSA in Java and learning full-stack web development with the MERN stack. The goal is to be a developer who writes secure software from the start, not one who patches it afterwards.

---

## Projects

- **[Deception & Log Integrity](https://github.com/Likhamba-Rongmei/deception-log-integrity)**: A Flask honeypot (decoy admin login portal) that records visitor IPs, user agents and credential attempts, flags brute force per IP, and escapes attacker input on its alert dashboard to prevent stored XSS. Paired with a tamper-evident logger that hash-chains entries with SHA-256 and pinpoints edited, deleted or reordered records.

- **[AWS Cloud SOC Lab](https://github.com/Likhamba-Rongmei/AWS-Cloud-SOC-Lab-Attack-Simulation-Detection)**: Simulated IAM privilege escalation (T1098), public S3 exposure (T1530) and EC2 persistence (T1078) on a live AWS account. Detected each attack by querying raw CloudTrail events from the CLI, without GuardDuty or Security Hub, then handled containment and remediation.

- **[Wazuh SIEM Implementation](https://github.com/Likhamba-Rongmei/Wazuh-SIEM-Implementation)**: Multi-host SOC lab (Ubuntu SIEM server, Windows 11 endpoint, macOS analyst station). Extended the agent config to ingest Windows Defender logs, validated brute-force (Event ID 4625) and malware (EICAR, Event ID 1116) detections, and fixed real deployment issues along the way: ARM64 incompatibility, audit policy and agent connectivity.

---

## Research

**BRIDGE: An Audited Cross-Dataset Benchmark for IoT Intrusion Detection**
*Second author (of 7) · In revision at Springer Journal of Network and Systems Management*

BRIDGE unifies four public intrusion datasets, produced by three different feature-extraction toolchains, under one 46-feature schema. It first audits them for defects (up to 48.4% duplicate records, broken or missing labels). Under a leakage-controlled leave-one-dataset-out protocol, it shows that no evaluated model transfers across datasets beyond a trivial baseline, so cross-dataset IoT intrusion detection remains an open problem. My role: investigation, visualisation, and review and editing of the manuscript.

[Code & benchmark](https://github.com/Ammar-ss/TCH-Net) · [arXiv (earlier version)](https://arxiv.org/abs/2604.11324)

---

## Currently

- Practising DSA in Java
- Learning the MERN stack (MongoDB, Express, React, Node.js)
- TryHackMe Jr Penetration Tester path, top 5% globally

---

## Stack

| Area | Tools |
|---|---|
| Languages | Java, JavaScript, C, SQL, Python |
| Web | HTML/CSS, REST APIs, Git, GitHub |
| Cloud & Systems | AWS (IAM, EC2, S3, VPC, CloudTrail), Linux (Ubuntu), Windows |
| Security | Log Analysis, Incident Response, Alert Triage, MITRE ATT&CK, OWASP Top 10 |
| Security Tools | Wazuh SIEM, Wireshark, Burp Suite, Nmap, Metasploit |

---

## Certifications

**CompTIA Security+ (SY0-701)** · Valid Jan 2026 – Jan 2029 · [Verify on Credly](https://www.credly.com/badges/4d6f6fe6-6885-4372-afb8-be4be5df92d6/public_url)

---

## Presence

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_5%25-212C42?style=flat-square&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/Hackermaan)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Likhamba-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/likhamba-rongmei)
[![Portfolio](https://img.shields.io/badge/Portfolio-likhamba--rongmei.github.io-black?style=flat-square)](https://likhamba-rongmei.github.io)
[![Email](https://img.shields.io/badge/Email-likhambarong%40gmail.com-grey?style=flat-square&logo=gmail)](mailto:likhambarong@gmail.com)
