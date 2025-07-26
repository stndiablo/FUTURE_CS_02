# SOC Task 2 – Security Alert Monitoring & Incident Response

## 🔍 Task Overview

Monitor and analyze simulated security alerts using a SIEM tool, identify suspicious activities, classify incidents, and generate an incident response report.

## 🧠 Tools Used

- Splunk Cloud (Free Trial)
- Sample log file: `SOC_Task2_Sample_Logs.txt`

---

## 🧾 Incident Summary – Malware Detection

**Date:** July 3, 2025  
**Search Query Used:**
```spl
index=main "malware detected"

---

## Threats Detected:

Trojan Detected
Ransomware Behavior
Rootkit Signature
Spyware Alert
Worm Infection Attempt

---

## Affected Users:

bob
charlie
david
eve

---

## IPs Involved:
172.16.0.3
10.0.0.5
203.0.113.77
198.51.100.42
192.168.1.101

---

## 🛠️ Recommendations

- Quarantine all affected systems immediately  
- Run endpoint antivirus and EDR scans  
- Investigate repeated alerts from user `bob` and IP `203.0.113.77`  
- Block identified IPs at firewall level if applicable  
- Conduct deeper review of login, file access, and malware timelines  
- Reimage infected systems if persistence is suspected

---

## ✅ Skills Gained

- Hands-on SIEM use (Splunk Cloud)  
- Writing and running SPL queries  
- Analyzing structured logs  
- Detecting and classifying malware threats  
- Drafting a basic incident response report
