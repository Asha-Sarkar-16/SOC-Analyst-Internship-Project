# SOC-Analyst-Internship-Project
SOC Monitoring Dashboard built on Splunk SIEM — Razz Security Internship | Threat Detection, Incident Response, False Positive Analysis
# 🛡️ SOC Analyst L1 — Security Monitoring Project
**Organisation:** Razz Security (Internship)
**Analyst:** Asha Latha Sarkar
**Period:** October 2025 | **Tool:** Splunk SIEM

---

## 📋 Project Overview
Simulated a real SOC Analyst L1 workday by ingesting 520 security 
events into Splunk, triaging 166 alerts, detecting 4 critical 
incidents, and building a live 6-panel monitoring dashboard.

---

## 📊 Dashboard Preview
![SOC Dashboard](dashboard_screenshot.pdf)

---

## 🔍 Incidents Detected

| ID | Incident | Severity | MITRE ATT&CK |
|---|---|---|---|
| IR-001 | C2 Command & Control Communication | 🔴 CRITICAL | T1071, T1090.003, T1571 |
| IR-002 | Distributed SSH Brute Force | 🟠 HIGH | T1110, T1110.004 |
| IR-003 | Network Port Scan / Reconnaissance | 🟠 HIGH | T1046, T1595 |
| IR-004 | Privilege Escalation | 🟠 HIGH | T1068, T1078 |

---

## 📈 Key Metrics

- ✅ **520** security events monitored (1 full day)
- ✅ **166** alerts triaged (CRITICAL: 20 | HIGH: 55 | WARNING: 91)
- ✅ **33** false positives identified (~36% of WARNING alerts)
- ✅ **4** confirmed incidents documented
- ✅ **6-panel** live Splunk dashboard built

---

## 🛠️ Tools Used
`Splunk SIEM` `Wazuh` `Wireshark` `VirusTotal` `Python`

## 📂 Repository Contents

| File | Description |
|---|---|
| `soc_security_logs_razzsecurity.csv` | 520-event security log file |
| `Incident_Report_IR-2025-OCT-001.docx` | Full 4-incident report |
| `SOC_Project_Complete_Guide.docx` | Step-by-step project guide |
| `dashboard_screenshot.png` | Live Splunk dashboard |

---

## 🎯 Skills Demonstrated
- SIEM Monitoring & Alert Triage
- Threat Detection (Brute Force, C2, Port Scan, Privilege Escalation)
- False Positive Reduction (~36%)
- MITRE ATT&CK Framework Mapping
- Incident Report Writing (NIST IR lifecycle)
