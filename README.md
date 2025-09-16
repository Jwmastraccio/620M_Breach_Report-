# 620M_Breach_Report

# Dark Web Breach Monitoring Reports

This repository contains threat intelligence reports focused on **dark web breaches and leaked datasets**. Each report is designed as a professional intelligence product, including:

- **Executive Summary** – Key highlights and impact of the breach  
- **Threat Actor Background** – Known actors or sellers involved  
- **Breach/Campaign Analysis** – Overview of affected platforms, data types, and potential risks  
- **MITRE ATT&CK Mapping** – Relevant TTPs observed in the campaign  
- **Indicators of Compromise (IOCs)** – Redacted or safe sample data for analysis  
- **Defensive Recommendations** – Actionable steps for organizations to mitigate risk  

---

## Projects

### 1. 2019 620 Million Accounts Breach
- **Platforms Affected:** 500px, Dubsmash, MyFitnessPal, MyHeritage, EyeEm, 8fit, Animoto, and more  
- **Data Compromised:** Email addresses, usernames, hashed passwords, personal information (birth date, city, gender)  
- **Threat Type:** Credential theft, account takeover, phishing, and spam  
- **MITRE ATT&CK IDs:**  
  - T1078: Valid Accounts  
  - T1003: Credential Dumping  

**Deliverables:**  
- [`Report.md`](./620M_Breach_Report/Report.md) – Full analysis and report  
- [`IOCs.csv`](./620M_Breach_Report/IOCs.csv) – Safe, redacted dataset of compromised accounts  
- [`Sources.pdf`](./620M_Breach_Report/Sources.pdf) – References from news articles and breach announcements  

---

## Skills Demonstrated
- OSINT investigation and analysis of dark web leaks  
- Mapping threat activity to MITRE ATT&CK framework  
- Documentation of IOCs suitable for SIEM/EDR ingestion  
- Communicating technical findings in a clear, professional format  
- Redacting sensitive data for safe sharing while maintaining analytical value  

---

## How to Use
- Review `Report.md` for detailed analysis  
- Import `IOCs.csv` into analysis or SIEM platforms (for testing and demonstration only, with redacted data)  
- Reference `Sources.pdf` for supporting evidence  

---

> ⚠️ **Note:** All datasets in this repository are **redacted and safe** for public sharing. No real personal information is included.
