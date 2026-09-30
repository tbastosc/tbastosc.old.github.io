---
layout: default
title: Tiago Bastos
---

<p align="center">
  <em>Detection starts with visibility, response starts with preparation. Good security is built, not bought.</em>
  <br><br>
  🇵🇹 Portuguese · 🇬🇧 English · 🇫🇷 French
</p>

<p align="center">
  <a href="#skills">🛠️ Skills &amp; Tools</a> ·
  <a href="#projects">🚀 Projects</a> ·
  <a href="#writeups">📝 Write-ups</a> ·
  <a href="#runbooks">📘 Runbooks</a> ·
  <a href="#notes">🗒️ Notes &amp; CheatSheets</a> ·
  <a href="#certs">🏆 Certifications</a> ·
  <a href="#contact">📬 Contact</a>
</p>

---

## 👤 About me {#about}

Early-career **Network & Cybersecurity Administrator** with hands-on experience in **Security Operations and Incident Response**. My background in military technical operations, mechatronics and industrial automation gives me a practical view of the security challenges where **IT meets OT**.

- 🔎 SOC work: alert triage, phishing response, detection engineering (SIEM/SOAR, EDR/XDR)
- 🌐 Networking: segmentation, firewalls, Zero Trust access, hardening
- 🧪 I learn by building: my Proxmox homelab is my training ground for blue team defense
- 🎯 Aiming for: full-time **SOC Analyst** → threat detection, investigation and IR

> **Now:** SC-200 ✅ · working towards **Cisco CCNA** and **HTB CDSA**

---

## 🛠️ Skills & Tools {#skills}

| Area | Skills / Tools |
|---|---|
| **SIEM / SOC** | ![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?logo=microsoftazure&logoColor=white) ![Wazuh](https://img.shields.io/badge/Wazuh-005EB8) ![Security Onion](https://img.shields.io/badge/Security_Onion-1F2937) ![Kibana](https://img.shields.io/badge/Kibana-005571?logo=kibana&logoColor=white) ![Google SecOps](https://img.shields.io/badge/Google_SecOps-4285F4?logo=google&logoColor=white) |
| **Detection & Hunting** | KQL · YARA-L · YARA · Sigma-style rules · MITRE ATT&CK · IOC investigation |
| **IR & Threat Intel** | ![TheHive](https://img.shields.io/badge/TheHive-F5A623) ![Cortex](https://img.shields.io/badge/Cortex-1F6FEB) ![MISP](https://img.shields.io/badge/MISP-2C3E50) Google Threat Intelligence |
| **Endpoint & Email** | Microsoft Defender XDR · Defender for O365 · Defender for Cloud · CrowdStrike Falcon · Sysmon |
| **Network Security** | ![pfSense](https://img.shields.io/badge/pfSense-212121?logo=pfsense&logoColor=white) ![Suricata](https://img.shields.io/badge/Suricata-EF3B2D) ![Zeek](https://img.shields.io/badge/Zeek-0A0A0A) VLANs/VLSM · DMZ · ACLs · ModSecurity WAF |
| **Zero Trust** | ![Cloudflare](https://img.shields.io/badge/Cloudflare_ZT-F38020?logo=cloudflare&logoColor=white) ![Twingate](https://img.shields.io/badge/Twingate-000000) Reverse proxy |
| **Offensive** | ![Kali](https://img.shields.io/badge/Kali_Linux-557C94?logo=kalilinux&logoColor=white) ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?logo=metasploit&logoColor=white) MITRE Caldera |
| **Vulnerability Mgmt** | ![Nessus](https://img.shields.io/badge/Tenable_Nessus-00C1DE) Risk assessment · GRC |
| **Systems** | ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) Windows Server · Active Directory · GPO · Fail2ban · auditd · AppArmor · UFW |
| **Cloud** | ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white) Log Analytics |
| **Virtualization** | ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) Portainer · Cisco Packet Tracer |
| **Programming** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white) C++ · SQL · KQL |
| **OT / Industrial** | Siemens TIA Portal · SCADA · Industrial networks · CNC · Automation *(background)* |
| **Maker** | 3D printing · Klipper · Fusion 360 *(hobby)* |

---

## 🚀 Projects {#projects}

<details markdown="1">
<summary><b>Secure Infrastructure for company Codesecure (Network-Cybersecurity-Administrator-Assessment-Project) »</b></summary>

`Cesae Digital · 01/2026 – 03/2026` · 📂 [**View Repository**](https://github.com/tbastosc/Network-Cybersecurity-Adminitrator-Assessment-Project)

Designed and implemented a segmented, secure IT infrastructure (**defense-in-depth + ZTNA**) for a simulated company with **120 hosted websites and 14 client VMs**.

| Domain | What I built |
|---|---|
| 🌐 **Network** | VLANs/VLSM, DMZ, ACLs, pfSense perimeter firewall |
| 🔐 **Secure Access** | ZTNA via Cloudflare, reverse proxy shielding internal web servers |
| ⚔️ **Pentesting** | Attack on a vulnerable Drupal server: SQL injection → root, mapped to MITRE ATT&CK |
| 📋 **Risk Assessment** | Formal analysis of **19 critical assets** with mitigations |
| 🧱 **Hardening** | Linux: UFW, SSH, Fail2ban, auditd, AppArmor, ModSecurity WAF · Windows/AD: GPOs, lockout policies, UAC, RDP restriction |
| 📡 **SIEM** | rsyslog + Wazuh with active response for brute-force, SQLi and malware (YARA) |

`Packet Tracer` `pfSense` `Wazuh` `Active Directory` `Linux` `Nessus` `GRC` `MITRE ATT&CK`

</details>

<details markdown="1">
<summary><b>Threat Hunting - Sentinel & Defender XDR »</b></summary>

`05/2026 – 08/2026` · 📂 [Repository](https://github.com/tbastosc/sentinel-defender-xdr-threat-hunting) · 📄 [KQL queries](https://github.com/tbastosc/sentinel-defender-xdr-threat-hunting)

Hands-on Azure lab built while preparing for the **SC-200** (Security Operations Analyst Associate).

- Deployed a **Sentinel workspace**, data connectors and endpoints for telemetry
- Built **analytics rules** (including multistage attack detection) and custom detections
- Incident management, investigation and **hunting for MITRE ATT&CK techniques with KQL**
- Used watchlists, **threat intelligence IOCs** and Content Hub solutions

`Microsoft Sentinel` `Azure Log Analytics` `KQL` `Microsoft Defender` `MITRE ATT&CK`

</details>

<details markdown="1">
<summary><b>Security SOC lab - Proxmox server (WIP) »</b></summary>

`05/2026 – Current` · 📂 [Repository (WIP)](https://github.com/tbastosc/proxmox-homelab) · 📄 [Documentation](https://github.com/tbastosc/proxmox-homelab/tree/main/docs)

Self-hosted Proxmox environment split into a **cybersecurity lab** and a **personal cloud**, used to practice alert triage, investigation, containment and remediation.

<pre class="mermaid">
flowchart LR
    A["Remote access<br/>Twingate + Cloudflare ZT"] --> B["pfSense<br/>VLANs"]
    B --> C[Security Lab]
    B --> D[Self-Hosted Cloud]
    C --> C1["Security Onion · Wazuh<br/>Suricata · Zeek"]
    C --> C2["TheHive · Cortex · MISP"]
    C --> C3["AD · Kali · Caldera<br/>VulnHub targets"]
    D --> D1["Jellyfin · Immich<br/>Backups"]
</pre>

- 🛡️ **Blue team:** Security Onion, Wazuh, Suricata/Zeek, TheHive/Cortex, Kibana, MISP
- 🔍 **Vuln scanning:** Tenable/Nessus
- ⚔️ **Red team:** Kali, Metasploit, MITRE Caldera, VulnHub, Active Directory attack/defense
- 🐳 **Tooling:** Docker / Portainer
- ☁️ **Self-hosted cloud:** Jellyfin, Immich, personal backups

`Proxmox` `pfSense` `VLANs` `Twingate` `Cloudflare ZT` `Security Onion` `Wazuh` `TheHive` `MISP` `Kali` `Docker`

</details>

---

## 📝 Write-ups {#writeups}

📂 **All write-ups:** [github.com/tbastosc/writeups](https://github.com/tbastosc/writeups)

---

## 📘 Runbooks and Playbooks {#runbooks}

| Document | Links |
|---|---|
| 📂 **Threat Hunting with KQL** | [PT](https://github.com/tbastosc/docs-runbooks-playbooks/blob/main/playbook_threat_hunting_kql.md) · [ENG](https://github.com/tbastosc/docs-runbooks-playbooks/blob/main/playbook_threat_hunting_kql_EN.md) |
| 📂 **Unlocking Machines - CrowdStrike** | [PT](https://github.com/tbastosc/docs-runbooks-playbooks/blob/main/runbook_desbloqueio_crowdstrike.md) |
| 📂 **Phishing Runbook - GSO** | [PT](https://github.com/tbastosc/docs-runbooks-playbooks/blob/main/runbook_phishing.md) |

---

## 🗒️ Notes and CheatSheets {#notes}

| Document | Link |
|---|---|
| 📂 **Linux CheatSheet: Fundamentals to Advanced (PT)** | [View](https://tbastosc.github.io/linux-cheatsheet) |
| 📂 **Microsoft CheatSheet: Fundamentals to Advanced (PT)** | [View](https://tbastosc.github.io/microsoft-cheatsheet) |

---

## 🏆 Certifications & Training {#certs}

| Status | Certification | Note |
|:--:|---|---|
| ✅ | Microsoft Certified: Security Operations Analyst Associate (SC-200) | |
| ✅ | Network Administration and Cybersecurity (09/2025 – 05/2026) | |
| ✅ | Introduction to Cybersecurity (2025) | |
| ✅ | Python programming languages (2024–2025) | |
| ✅ | Advanced Course in Automation and Robotics (2023–2025) | |
| ✅ | CET Level 5: Specialist Technician in Mechatronics (2020–2022) | |
| 🟡 | **Cisco CCNA** | In progress |
| 🟡 | **HTB Certified Defensive Security Analyst (CDSA)** | In progress |
| 🟡 | **CyberDefenders Certified CyberDefender (CCDL1/2)** | Planned |

---

## 📬 Contact {#contact}

Open to **SOC Analyst** and **network security** opportunities.

- 💼 [LinkedIn](https://linkedin.com/in/tiago-cbastos/)
- 📧 [tbastosc@gmail.com](mailto:tbastosc@gmail.com)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tbastosc&label=Visitors&color=0e75b6&style=flat-square" alt="Profile views">
</p>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true, theme: "dark" });
</script>
