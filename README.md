# 🔐 Automated Brute-Force Detection Workflow

![Security](https://img.shields.io/badge/Type-SOC%20Simulation-blue)
![SIEM](https://img.shields.io/badge/Tool-Splunk-green)
![Python](https://img.shields.io/badge/Language-Python3-yellow)

## 📌 Project Overview
A simulated SOC (Security Operations Center) project to detect and 
automatically respond to brute-force attacks using Splunk SIEM, 
custom SPL detection rules, and Python automation.

## 🛠️ Tools & Technologies
- **Kali Linux** – Attack simulation
- **Hydra** – Brute-force tool
- **Windows OS** – Target system
- **Splunk SIEM** – Log analysis & alerting
- **SPL** – Custom detection queries
- **Python 3** – Automated response scripts

## 🎯 Objectives
- Simulate brute-force attacks using Hydra
- Detect Event ID 4625 (Failed Logon) in Splunk
- Build custom SPL alerting rules
- Automate IP blocking via Python scripts

## 📊 Key Findings
| Finding | Severity | Status |
|---------|----------|--------|
| 200+ Event 4625 alerts in 2 mins | High | Detected |
| SPL rules flagged IP after 5 failures | High | Mitigated |
| Credential spraying pattern identified | Medium | Detected |
| Python auto-blocked malicious IP | High | Resolved |

## 📁 Repository Structure
brute-force-detection-soc/
├── reports/
│   └── Security_Audit_Report.pdf
├── scripts/
│   └── ip_blocker.py
├── splunk/
│   └── detection_rules.spl
└── README.md

## ⚠️ Disclaimer
This project was conducted in a **controlled lab environment** 
for educational purposes only.
