# Hi, I'm Mazen 👋

**Technical Project Manager · Cybersecurity · Test Management** · Stuttgart, Germany

PMP-certified Technical Project Manager with 10 years in safety-critical automotive and embedded software, from embedded development and test management to end-to-end delivery of multi-team projects at CETITEC (Porsche Group), Bosch and Valeo. Growing into cybersecurity through documented incident investigations (ransomware, insider threats, nation-state intrusions, an attack on power-grid SCADA systems) and hands-on labs in SIEM detection engineering, endpoint monitoring and web application protection.

- 📋 **Project delivery:** planning, risk management, stakeholder reporting, AI-assisted PM workflows
- 🛡️ **Security operations:** incident response, KQL threat hunting, SIEM (Microsoft Sentinel, Wazuh), Microsoft Defender XDR threat intelligence, alert triage, MITRE ATT&CK (Enterprise & ICS)
- 🌐 **Application & infrastructure security:** web application firewall (SafeLine), reverse proxy & TLS, CIS benchmarks, Azure, Linux
- 🧪 **Quality:** test strategy, validation, traceability, defect management

---

## 🔎 SOC Investigations

End-to-end incident investigations in KQL, each written up as an incident report with timeline, IOCs, MITRE ATT&CK mapping, response plan and detection rules.

| Investigation | What it shows | Stack |
|---------------|---------------|-------|
| [Insider Threats & Domain-Wide Ransomware](https://github.com/MazenYousef/soc-encryptodera-insider-threat-investigation) | Three overlapping incidents across 10 log sources: ransomware on 306 hosts traced back through GPO, domain admin, Mimikatz and lateral movement to a departed employee's hijacked account; two insiders exfiltrating data via USB and FTP | KQL · Incident Response · MITRE ATT&CK |
| [Power Grid SCADA Attack (ICS/OT)](https://github.com/MazenYousef/soc-chicago-grid-ics-investigation) | Critical-infrastructure attack causing a city-wide blackout, traced from phishing and account takeover through internal spearphishing of a SCADA operator, the BlackEnergy implant and PsExec spread to a KillDisk wiper; attributed to Sandworm (APT44) | KQL · ICS/SCADA · MITRE ATT&CK for ICS |
| [Nation-State Attribution with Microsoft Defender XDR](https://github.com/MazenYousef/soc-titanshield-defender-xdr-investigation) | Two APT campaigns (Moonstone Sleet, Crimson Sandstorm) attributed with Defender XDR Threat Intelligence: trojanized game and romance lure, recon via passive DNS, a "low-fidelity" EDR alert escalated to 15 hosts | Defender XDR TI · KQL · Passive DNS |
| [Phishing → C2 Beaconing](https://github.com/MazenYousef/soc-whiskermania-network-investigation) | Network-focused hunt across DNS, flow, proxy and email logs: lookalike-domain phishing, HTTPS beaconing, scoping and behaviour-based detections | KQL · Network Analysis |

## 🧪 Security Home Labs

| Lab | What it shows | Stack |
|-----|---------------|-------|
| [Azure Sentinel Honeypot](https://github.com/MazenYousef/soc-azure-sentinel-honeypot-lab) | Cloud SIEM on real attack traffic: exposed Windows honeypot → Sentinel, brute-force detection in KQL, GeoIP analysis, scheduled analytics rule | Azure · Sentinel · KQL · AMA/DCR |
| [Wazuh SIEM/XDR](https://github.com/MazenYousef/soc-wazuh-siem-home-lab) | Open-source SIEM on-prem: Windows agent onboarding, real-time File Integrity Monitoring, CIS benchmark assessment | Wazuh · Ubuntu · VirtualBox |
| [SafeLine Web Application Firewall](https://github.com/MazenYousef/safeline-waf-dvwa-home-lab) | WAF as an HTTPS reverse proxy in front of DVWA: TLS, custom deny rules, HTTP flood protection, WAF bypass analysis | SafeLine · DVWA · Kali · OpenSSL |

## ⚙️ AI-Powered Project Management Tools

| Project | What it does | Stack |
|---------|--------------|-------|
| [Weekly Status Report Generator](https://github.com/MazenYousef/pm-status-report-generator) | Pulls GitHub/Jira issues and generates a stakeholder-ready weekly report (Markdown + PDF) on a schedule | Python · Claude API · GitHub Actions · Jira API |
| [Meeting Notes → Action Item Extractor](https://github.com/MazenYousef/pm-meeting-action-extractor) | Turns raw meeting notes into deduplicated GitHub Issues or Jira tickets | Python · Claude API · GitHub Actions · Jira API |

---

## 📑 Certifications

**Security**
- [CompTIA Security+](https://www.credly.com/badges/b10e87f6-e65d-4952-a885-384278df3980/public_url)
- [ISC2 Certified in Cybersecurity (CC)](https://www.credly.com/badges/ce20276c-0c45-40ce-a1f3-04139c592ae8/public_url)
- [Microsoft SC-900: Security, Compliance, and Identity Fundamentals](https://learn.microsoft.com/en-us/users/mazenyousef-0847/credentials/dfaf75ac62fb2400)

**Project & Quality Management**
- [Project Management Professional (PMP)](https://www.credly.com/badges/51a833c9-1789-41db-9c82-eb63fe2f5e79/linked_in_profile)
- ISTQB Certified Tester Foundation Level (CTFL)

**Training & Hands-on**
- [Ironhack Cybersecurity Bootcamp](https://www.credential.net/9b4ef5ae-af21-4f6f-a8bf-27f22573f185)
- [TryHackMe: Cyber Security 101](https://tryhackme.com/certificate/THM-SZYDQUZ9LF)
- TryHackMe: SOC Level 1
- LetsDefend: SOC alert triage practice

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mazenyousef-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/mazenyousef)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Mazen.Yousef-212C42?logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Mazen.Yousef)
