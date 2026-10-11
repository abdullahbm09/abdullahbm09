<div align="center">

<h1>Abdullah Bin Masood, PhD</h1>
<h3>Penetration Testing · Red Team · Incident Response · SIEM & Detection · PCI DSS</h3>
<h4>Co-Founder & Security Lead @ Data Pulse Technologies &nbsp;·&nbsp; Lecturer @ Munster Technological University &nbsp;·&nbsp; Dublin, Ireland</h4>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdullah_Bin_Masood-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdullahbinmasood)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-abdullahbm09-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/abdullahbm09)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Publications-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=CiqKoMQAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--4474--0011-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-4474-0011)
[![Email](https://img.shields.io/badge/abdullahbm09%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abdullahbm09@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=abdullahbm09&style=flat-square&color=blue)

<br/>

**🟢 Open to roles in Ireland (Dublin · Cork · Remote)** &nbsp;·&nbsp; Stamp 4 — full right to work, no sponsorship required

</div>

---

## About

Cybersecurity practitioner working across the **full attack-and-defence lifecycle** — penetration testing and red team, incident response and forensic investigation, SIEM detection engineering, vulnerability management, and PCI DSS / NIST / ISO compliance.

Led offensive security on a **Dell Technologies–funded** red team programme against a live cloud-robotic Industry 4.0 environment. Own the security programme end-to-end at Data Pulse Technologies, including the **PCI DSS Level 1** workstream for the PBT Payment Gateway (Azure/Kubernetes, 1,000+ merchants). Lecture at MTU on incident response, SIEM and vulnerability assessment to postgraduate industry professionals.

PhD in AI-driven intrusion detection for industrial control systems · 7 peer-reviewed publications.

---

## What I Do

**Offensive Security**
- Red team attack-chain design and execution — reconnaissance → initial access → privilege escalation → lateral movement → impact
- CVE exploitation and exploit chaining (recent: CVE-2023-38408, CVSS 9.8)
- Web and infrastructure penetration testing · Adversarial ML (FGSM)
- MITRE ATT&CK TTP mapping · CVSS / RVSS scoring frameworks

**Incident Response & Detection Engineering**
- Full IR lifecycle to NIST SP 800-61r3 and ISO 27035
- SIEM: Splunk, Elastic Stack, Wazuh · Microsoft Defender EDR
- Detection engineering with custom Sigma and YARA rules · IoC-based triage
- Forensic triage · Root cause analysis · Executive-ready incident reporting

**Security Engineering, Cloud & Compliance**
- PCI DSS Level 1 remediation and audit readiness
- Azure / Kubernetes hardening · Jenkins + NGINX secure CI/CD
- NIST CSF 2.0 · ISO 27001 · ISO 27035 · ISO 42001 · DORA · OWASP Top 10
- Vulnerability management (Nessus, OpenVAS) driven to closure

**Teaching (MTU Cork)**
- Cyber Incident Response · Log & Event Analysis · Vulnerability Assessment & Penetration Testing · Secure Network Systems
- Hands-on labs on the CYRIN enterprise cyber range: Nessus, OpenVAS, Metasploit, Burp Suite, Splunk, Elastic, Sigma, YARA

---

## Highlighted Work

### 🔴 Cloud-Robotics Red Team — Dell Technologies–Funded (2024–2025)
Two end-to-end attack chains against a live cloud-robotic Industry 4.0 quality-control environment.

- **Chain 1 — SROS2 permission-file misconfiguration (CVSS 8.5):** bypassed access control and hijacked robotic-arm trajectory commands in the production control loop
- **Chain 2 — CVE-2023-38408 (OpenSSH agent forwarding, CVSS 9.8):** lateral movement edge → cloud + root privesc via Python sudo misconfiguration + **FGSM adversarial poisoning** of a deployed CNN (+111% misclassification)
- **46 MITRE ATT&CK techniques across 10 tactics;** novel CVSS/RVSS-based Security Assurance Evaluation framework delivered to Dell
- Full technical + executive report submitted to **IEEE Access**

→ [`cloud-robotics-redteam`](https://github.com/abdullahbm09/cloud-robotics-redteam)

### 💳 PBT Payment Gateway — PCI DSS Level 1 Security Lead (2023–Present)
Owned the security workstream for a PCI DSS Level 1 Azure/Kubernetes payment gateway processing hundreds of millions of Euros across 20+ European currencies.

- Led PCI DSS certification: **remediated every external and internal network vulnerability** raised in PCI testing (remediation report accepted), closed exposures across the internal Azure network, drafted the cardholder-database segmentation plan
- Production hardening: **per-node memory 112% → 70%**, **Azure spend −44.79%**, recurring pod crash fixed, Kubernetes scheduler resource maps built
- Secure CI/CD: patched + reverse-proxied **NGINX in front of Jenkins**, committed Jenkinsfiles and CI test templates across every repository, deployed the card-issuing service to staging and production
- SIEM + EDR: **Wazuh** with custom Sigma/YARA rules, **Microsoft Defender for EDR**, OWASP Top 10 (2021 & 2025) assessments driven to closure with developers

→ [`Data Pulse case study`](https://datapulsetechnologies.org/case-studies/pbt-payment-solutions)

### 🧠 DD-IDS — Data-Driven IDS for IIoT Smart Factories (PhD Research)
PCA with Hotelling T² and SPE statistics for false-data-injection detection on industrial control systems. Detection, identification and reconfiguration logic embedded into an **Ethereum smart contract** — immutable thresholds and cryptographically verifiable control loop.

- Validated across **9 attack scenarios** on the Tennessee Eastman benchmark
- **Up to 59% reduction** in control-loop deviation under sustained attack
- Published in *Computer Communications* (Elsevier, 2023)
- Companion work: **Block-DRL** — blockchain + A2C deep reinforcement learning for secure IIoT computation offloading; **7× reward convergence** vs. DQN baseline at ~half the execution time

→ [`dd-ids-iot`](https://github.com/abdullahbm09/dd-ids-iot) · [DOI](https://doi.org/10.1016/j.comcom.2023.02.015)

### 🚨 WordPress Backdoor — Incident Response & Remediation (2026)
Independent engagement: persistent SEO-spam backdoor on an SME WordPress site, surviving previous cleanup attempts.

- Forensically triaged **19,855 files** to identify initial access and persistence mechanisms
- Removed **1,448+ injected spam posts**, CSS-obfuscated SEO-spam links and rogue administrator accounts
- Rotated credentials, hardened host + CMS, delivered a client incident report aligned to **NIST SP 800-61r3**

---

## Currently Building

| Project | Status |
|---------|--------|
| `security-writeups` — HTB + VulnHub offensive methodology writeups | 🔨 In progress |
| `xai-ids-research` — SHAP / LIME framework for OT/IIoT IDS | 🔨 In progress |
| **eJPT** — eLearnSecurity Junior Penetration Tester | 📚 In progress |
| **BTL1** — Blue Team Level 1 | 📋 Next |
| **BTL2** — Blue Team Level 2 | 📋 Planned |
| **OSCP** — Offensive Security Certified Professional | 📋 Planned |

---

## Technical Skills

**Offensive Security**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=owasp&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-00C176?style=flat-square&logoColor=white)
![OpenVAS](https://img.shields.io/badge/OpenVAS-4CAF50?style=flat-square&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-BB0000?style=flat-square&logoColor=white)

**Defensive / SIEM / Incident Response**

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005C86?style=flat-square&logoColor=white)
![Microsoft Defender](https://img.shields.io/badge/Microsoft_Defender-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-8B0000?style=flat-square&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-2E86AB?style=flat-square&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-C0392B?style=flat-square&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-E6007E?style=flat-square&logoColor=white)

**Governance, Risk & Compliance**

![PCI DSS](https://img.shields.io/badge/PCI_DSS-005B9F?style=flat-square&logoColor=white)
![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF_2.0-003087?style=flat-square&logoColor=white)
![NIST 800-61](https://img.shields.io/badge/NIST_SP_800--61-003087?style=flat-square&logoColor=white)
![ISO 27001](https://img.shields.io/badge/ISO_27001-005F9E?style=flat-square&logoColor=white)
![ISO 27035](https://img.shields.io/badge/ISO_27035-005F9E?style=flat-square&logoColor=white)
![DORA](https://img.shields.io/badge/DORA-1B365D?style=flat-square&logoColor=white)
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-00549E?style=flat-square&logo=owasp&logoColor=white)

**Cloud, Infrastructure & DevSecOps**

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**AI / ML & Research**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)

---

## Selected Publications

- **Masood et al.** "A Blockchain-Based Data-Driven Fault-Tolerant Control System for Smart Factories in Industry 4.0" — *Computer Communications*, vol. 204, pp. 158–171, 2023
- **Masood et al.** "A Blockchain-Based Transactive Energy Management Scheme for Nano-Grids using Power Flow Coloring" — *IEEE ICCE*, Taiwan, 2023
- **Humza, Masood, Qureshi.** "LSM: A Lightweight Security Mechanism for IoT-Based Smart City Management Systems using Blockchain" — *IJIST*, 3(4), 2021
- **Masood et al.** "Closing the Loop in Cyber-Physical Systems using Blockchain: Microgrid Frequency Control Example" — *IEEE MENACOMM*, 2019
- **Masood et al.** *Under review (IEEE Access):* Security Assurance Evaluation Framework and Red Team Attack Chains from the Dell Technologies–Funded Cloud-Robotics Programme

Full list → [Google Scholar](https://scholar.google.com/citations?user=CiqKoMQAAAAJ)

---

<div align="center">
<sub>IEEE Member (since 2018) &nbsp;·&nbsp; Airbus CyberRange LADE &nbsp;·&nbsp; AWS Cloud Operations &nbsp;·&nbsp; PhD · University of Cyprus &nbsp;·&nbsp; MTU Cork</sub>
</div>
