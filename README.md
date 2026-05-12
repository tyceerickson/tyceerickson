# Hey, I'm Tyce Erickson 👋

I'm from Morgan, Utah — Eagle Scout, bodybuilder, and former bull rider. I didn't start in tech. I spent years diagnosing and repairing heavy equipment worth $100,000+ before finding my way into cybersecurity. That background taught me how to learn complex systems fast, stay calm under pressure, and finish what I start. I bring the same approach to everything I build here.

I'm entering **Carnegie Mellon University's MSISPM program (Fall 2026)** after completing my BS in Management Information Systems at Weber State University (GPA: 3.74). My focus is the intersection of **AI and security operations** — not just studying concepts, but deploying real infrastructure, running real attacks, and building real tools on top of it all.

---

## 🔐 Certifications

![Security+](https://img.shields.io/badge/CompTIA-Security%2B-red?style=flat-square&logo=comptia)
![Network+](https://img.shields.io/badge/CompTIA-Network%2B-red?style=flat-square&logo=comptia)
![CC](https://img.shields.io/badge/ISC2-CC-green?style=flat-square)

---

## 🧪 Portfolio Projects

These projects are built on a production-grade home cybersecurity lab featuring 4 isolated VLANs, an OPNsense stateful firewall, Kali Linux attacker, and multiple victim/vulnerable targets. Each project builds on the last.

---

### 🏗️ [Home Lab Infrastructure](https://github.com/tyceerickson/home-lab-infrastructure)
**Foundation | Documentation | Network Architecture**

Complete professional documentation of a segmented home cybersecurity lab. Covers VLAN architecture, firewall policy, IP addressing, port mapping, security design philosophy, and recovery procedures.

- 4 isolated VLANs (Management / Attacker / Victim / Enterprise)
- OPNsense stateful firewall with inter-VLAN routing
- Cisco Catalyst 2960, Netgear managed switch, Mac UTM hypervisor
- Professional documentation written to enterprise wiki standards

---

### 🤖 [AI Network Traffic Classifier](https://github.com/tyceerickson/ai-traffic-classifier)
**Machine Learning | Network Security | Python**

End-to-end ML pipeline that classifies network traffic as malicious or benign using a dataset generated entirely within the home lab. Model trained locally on an Alienware m16 R2 (RTX 4070, 64GB RAM).

- Generated real malicious traffic (Nmap, Metasploit, credential attacks) and benign traffic
- Captured and labeled dataset using Wireshark / tshark
- Built and trained a Random Forest classifier using scikit-learn
- Full Jupyter notebook walkthrough with evaluation metrics and visualizations

---

### 🍯 [Honeypot Deployment](https://github.com/tyceerickson/honeypot-deployment)
**Defensive Security | Threat Detection | Attack Analysis**

Deployed a honeypot on the isolated victim VLAN to capture and analyze real attack interactions. Attack data collected here feeds directly into the capstone SOC pipeline.

- Honeypot deployed on VLAN 30 with controlled attacker access from Kali (VLAN 20)
- Captured credential attacks, session commands, and exploit attempts
- Attack behavior mapped to MITRE ATT&CK framework
- Logs exported and formatted for SIEM ingestion

---

### 🛡️ [AI-Powered SOC Pipeline](https://github.com/tyceerickson/ai-soc-pipeline)
**AI + Security Operations | SIEM | Dashboard**

Capstone project — a three-phase AI-powered security operations pipeline built on real lab infrastructure and real attack data.

- **Phase 1 — AI Firewall Log Analyzer:** Python tool that feeds OPNsense logs to an AI API and returns plain-English threat summaries
- **Phase 2 — SIEM + AI Alert Summarizer:** Wazuh deployed on Ubuntu Server ingesting logs from all lab sources, with an AI layer that prioritizes and explains alerts
- **Phase 3 — SOC Dashboard:** Flask web dashboard aggregating all pipeline outputs with real-time alert visualization and AI-generated executive summaries

---

## 🛠️ Tech Stack

**Security**
`Kali Linux` `Metasploit` `Wireshark` `Nmap` `Wazuh` `OPNsense`

**AI / ML**
`Python` `scikit-learn` `pandas` `OpenAI API` `Ollama` `Jupyter`

**Infrastructure**
`VLANs` `Firewall Policy` `Cisco IOS` `UTM Hypervisor` `Ubuntu Server`

**Development**
`Flask` `HTML/CSS` `Git` `Bash`

---

## 🎓 Background

- **CMU MSISPM** — Fall 2026
- **Weber State University** — BS Management Information Systems, GPA 3.74
- **Carnegie Mellon** — Summer Security Intensive IT Lab Fellowship, 2025
- **CompTIA** — Security+, Network+
- **ISC2** — Certified in Cybersecurity (CC)
- **Boy Scouts of America** — Eagle Scout

---

## 📫 Connect

https://www.linkedin.com/in/tyceerickson/
tyceerickson@gmail.com
