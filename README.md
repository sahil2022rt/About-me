<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:58a6ff&height=200&section=header&text=Sahil%20Telote&fontSize=60&fontColor=e6edf3&fontAlignY=40&desc=Cloud%20Security%20%7C%20SOC%20Operations%20%7C%20Incident%20Response&descAlignY=62&descColor=8b949e&animation=fadeIn" alt="Header" />

<!-- Typing Animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&width=700&height=60&lines=🔐+Cloud+Security+%26+SOC+Analyst;🛡️+CEH+%7C+ISO+27001+Lead+Auditor+%7C+Google+Cloud+Certified;⚡+Building+Security+Automation+%26+Threat+Intel+Tools)](https://git.io/typing-svg)

<br>

<!-- Social Links — 4 only -->
[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-0d1117?style=for-the-badge&logoColor=58a6ff)](https://sahil2022rt.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-telote-2406b733b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sahil2022rt)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sahiltelote744@gmail.com)

<br>

![Profile Views](https://komarev.com/ghpvc/?username=sahil2022rt&color=58a6ff&style=flat-square&label=Profile+Views)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-3fb950?style=flat-square)
![Location](https://img.shields.io/badge/📍-Nagpur%2C%20India-8b949e?style=flat-square)

</div>

---

## 🧠 About Me

```python
class SahilTelote:
    role       = "Cloud Security & SOC Analyst (Entry-Level)"
    location   = "Nagpur, Maharashtra, India 🇮🇳"
    education  = "B.E. Computer Engineering — University of Mumbai (May 2026) | CGPA: 7.45"

    expertise  = [
        "Cloud Security — AWS & GCP",
        "SOC Operations & SIEM Alert Triage",
        "Incident Response (ITIL v4 Lifecycle)",
        "Malware Analysis — Static & Dynamic",
        "Threat Intelligence & MITRE ATT&CK",
        "Compliance: ISO/IEC 27001 | PCI DSS 3.2.1",
        "Security Automation with Python & Bash"
    ]

    highlights = {
        "honeypot"    : "Captured 1,200+ live brute-force attempts → mapped to MITRE ATT&CK TTPs",
        "malware_lab" : "Analyzed 50+ malware samples · 15+ custom YARA rules · 60% faster pipeline",
        "phishguard"  : "92% accuracy across 500+ messages · multi-language NLP · risk score 0–100",
        "gcp_capstone": "Remediated 3 critical cloud misconfigs aligned to PCI DSS 3.2.1"
    }

    status     = "🟢 Actively seeking roles in Cloud Security / SOC / Cybersecurity Operations"
```

---

## 🏆 Certifications

<div align="center">

| 🏅 Certification | 🏢 Issuer | 📅 |
|:---|:---:|:---:|
| **Certified Ethical Hacker (CEH)** | Cisco | Apr 2026 |
| **Google Cloud Cybersecurity Certificate** | Google Cloud | Jan 2026 |
| **ISO/IEC 27001:2022 Lead Auditor** | Mastermind | Dec 2025 |
| **Cisco AI Technical Practitioner (AITECH)** | Cisco | Mar 2026 |
| **Certified Threat Intelligence & Governance Analyst (CTIGA)** | Red Team Leaders | Jan 2026 |
| **Certified Red Team Operations Management (CRTOM)** | Red Team Leaders | Dec 2025 |
| **Cyber Security Architecture v1** | Red Team Leaders | Jan 2026 |
| **Introduction to Python for Defensive Security** | Red Team Leaders | Feb 2026 |
| **Detect, Respond & Recover – Cloud Cybersecurity** | Google | Jan 2026 |
| **Strategies for Cloud Security Risk Management** | Google | Sep 2025 |
| **Threat Modeling in Cybersecurity** | NASSCOM | Dec 2025 |
| **Cybersecurity Fundamentals** | IBM | Feb 2025 |
| **Linux Challenges** | KodeKloud | Aug 2025 |

</div>

> 🎯 **Currently pursuing:** CCNA (Cisco) · NSE 4 Fortinet Network Security Expert

---

## 🔬 Key Projects

<details>
<summary><b>🦠 Malware Analysis Sandbox — Static, Dynamic Analysis & Threat Intelligence</b> &nbsp;|&nbsp; Jan–Apr 2026</summary>

<br>

**Overview:** Full-cycle malware analysis lab for safe detonation, behavioral analysis, and structured intelligence reporting.

| Metric | Result |
|---|---|
| Samples Analyzed | 50+ (ransomware, trojans, RATs, stealers) |
| Custom YARA Rules | 15+ authored |
| Pipeline Speed | 60% faster per-sample analysis |
| ATT&CK Tactics Covered | Execution · Persistence · Defense Evasion · C2 · Exfiltration |

**What I built:**
- Isolated sandbox with Python + VirtualBox snapshots for safe malware detonation with automated VM orchestration
- **Static Analysis:** PE header inspection, entropy analysis, strings extraction, SHA-256/MD5 hashing; Ghidra + IDA Free for packed/obfuscated binaries
- **Dynamic Analysis:** API calls, registry modifications, file system changes, network traffic monitoring via Procmon, Sysmon, Wireshark/tcpdump
- Automated IoC extraction (IPs, domains, registry keys, file hashes) into structured JSON threat intel reports with ISO/IEC 27001-aligned severity scores

`Python` `VirtualBox` `Ghidra` `IDA Free` `Procmon` `Sysmon` `Wireshark` `YARA` `MITRE ATT&CK` `IoC Extraction`

</details>

<details>
<summary><b>🍯 SSH Honeypot — Live Incident Detection & Attacker Trend Analysis</b> &nbsp;|&nbsp; Nov 2025</summary>

<br>

**Overview:** Production SSH honeypot deployed to capture and forensically analyze real-world intrusion attempts.

| Metric | Result |
|---|---|
| Intrusion Attempts Captured | 1,200+ in 2 weeks |
| Attacker Commands Mapped | 40+ sequences |
| Tactics Covered | Initial Access · Execution · Persistence · Discovery |

**What I built:**
- Deployed fake shell honeypot emulating real SSH environment; captured attacker credentials, geographic origins, and full session behaviors
- Real-time Python logging pipeline comparable to Splunk alert correlation workflows
- Structured post-incident findings report with ISO/IEC 27001-aligned countermeasure recommendations (ServiceNow-style incident summary)

`Python` `Linux` `SSH` `Structured Logging` `MITRE ATT&CK` `Splunk-style Analysis` `Incident Reporting`

</details>

<details>
<summary><b>🛡️ PhishGuard AI — Real-Time Phishing Detection & Automated Triage</b> &nbsp;|&nbsp; Apr 2026</summary>

<br>

**Overview:** Multi-channel AI-powered phishing detection system with NLP, risk scoring, and automated triage.

| Metric | Result |
|---|---|
| Detection Accuracy | 92% across 500+ messages |
| False-Positive Rate | < 8% |
| Languages Supported | Hindi · Marathi · Tamil · English |
| Channels | SMS · Email · WhatsApp · Audio |

**What I built:**
- Risk scoring engine (0–100) with threat classification tags: OTP harvesting, urgency tactics, fake KYC/job scams, suspicious links
- Multi-language NLP detection covering 4 regional Indian languages for broader coverage
- Offline-capable security coach for real-time user guidance; live dashboard tracking High Risk / Suspicious / Safe messages

`Python` `NLP` `Pattern-Matching` `Risk Scoring` `Alert Architecture` `Security Automation` `Data Visualization`

</details>

<details>
<summary><b>☁️ Cloud Security Incident Remediation & PCI DSS Compliance (GCP Capstone)</b> &nbsp;|&nbsp; Jan 2026</summary>

<br>

**Overview:** End-to-end GCP security incident simulation with full PCI DSS 3.2.1-aligned remediation lifecycle.

**3 Critical Misconfigurations Remediated:**

| Vulnerability | Fix Applied |
|---|---|
| 🪣 Exposed public GCS buckets | Enforced uniform bucket-level access control |
| 🔥 Open firewall rules | Hardened with least-privilege network policies |
| 💻 Unprotected Compute Engine VMs | Deployed Shielded VMs, restored from trusted snapshots |

**What I did:**
- Used Security Command Center + IAM policy audits to identify and triage vulnerabilities
- Enabled Cloud Logging for full observability and compliance verification
- Authored comprehensive remediation runbook and IAM audit log — equivalent to ServiceNow change tracking

`GCP` `IAM` `Security Command Center` `Cloud Logging` `PCI DSS 3.2.1` `Compliance Documentation`

</details>

---

## 💼 Training & Simulations

| 🏢 Organization | 🎭 Role Simulated | 📅 | 🔍 Key Activities |
|:---|:---|:---:|:---|
| **Deloitte** (Forage) | SOC Analyst | Jul 2025 | SIEM log analysis · alert triage · ISO 27001 incident response · cloud security posture reviews · management bridge facilitation |
| **Mastercard** (Forage) | Cybersecurity Analyst | Jan 2025 | Security alert investigation · network log analysis · anomaly detection · ServiceNow-style remediation docs |
| **Tata Group** (Forage) | Cybersecurity Analyst | Jan 2024 | Vulnerability scanning · enterprise security frameworks · Jira-style risk-prioritized remediation reports |

---

## 💻 Tech Stack

**☁️ Cloud Platforms**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

**🔐 Security & SIEM**

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-00B388?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-red?style=flat-square)
![YARA](https://img.shields.io/badge/YARA-orange?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white)

**🛠️ Languages & Scripting**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)

**🗄️ Data & DevOps**

![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat-square&logo=mysql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-%2329B5E8.svg?style=flat-square&logo=snowflake&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=Apache%20Airflow&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-white?style=flat-square&logo=Matplotlib&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**🔧 ITSM & Collaboration**

![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat-square&logo=Canva&logoColor=white)

**📐 Frameworks & Standards**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-red?style=flat-square)
![ITIL v4](https://img.shields.io/badge/ITIL%20v4-6C4A9E?style=flat-square)
![ISO 27001](https://img.shields.io/badge/ISO%2027001-0052CC?style=flat-square)
![PCI DSS](https://img.shields.io/badge/PCI%20DSS%203.2.1-darkblue?style=flat-square)
![SAST/DAST](https://img.shields.io/badge/SAST%2FDAST-gray?style=flat-square)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.shion.dev/api?username=sahil2022rt&theme=github_dark&hide_border=true&include_all_commits=true&count_private=false&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&border_radius=10" height="165" />
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=sahil2022rt&theme=github_dark&hide_border=true&layout=compact&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&border_radius=10" height="165" />

<br>

<img src="https://streak-stats.demolab.com/?user=sahil2022rt&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff&border_radius=10" />

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sahil2022rt&theme=github-dark&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ff7b72&area=true" />

</div>

---

## 🗺️ 2025–2026 Roadmap

```
[✅] Certified Ethical Hacker (CEH)
[✅] ISO/IEC 27001:2022 Lead Auditor
[✅] Google Cloud Cybersecurity Certificate
[✅] CTIGA — Threat Intelligence & Governance Analyst
[✅] Malware Analysis Sandbox — 50+ samples, 15+ YARA rules
[✅] SSH Honeypot — 1,200+ live intrusion attempts
[✅] PhishGuard AI — 92% accuracy, 4 languages
[✅] GCP Cloud Security Capstone — PCI DSS 3.2.1 compliant
[🔄] CCNA — In Progress
[🔄] NSE 4 Fortinet — Planned
[🎯] Land first role: Cloud Security / SOC / Security Operations
```

---

## 🌐 Languages

`English — Full Professional` &nbsp;·&nbsp; `Hindi — Full Professional` &nbsp;·&nbsp; `Marathi — Native`

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,50:1a3a5c,100:0d1117&height=120&section=footer&text=Let%27s%20Connect%20%26%20Collaborate!&fontSize=24&fontColor=e6edf3&fontAlignY=55&animation=fadeIn" />

*"Security is not a product, but a process." — Bruce Schneier*

</div>
