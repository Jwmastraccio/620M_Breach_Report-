# Dark Web Monitoring Report
## 2019 620 Million Accounts Breach

---

### 1. Executive Summary
In February 2019, multiple websites reported a major data breach affecting approximately **620 million accounts** across 16 platforms.
Data included usernames, email addresses, hashed passwords, and in some cases PII (birth dates, locations).
The Stolen data was advertised on the dark web (Dream Market) for cryptocurrancy.
This breach demonstrates the **risks of credential reuse and the monetization of stolen accounts** by cybercriminals.

---

### 2. Threat Actor Background
-**Unknown seller(s)** on Dream Market (Tor-based marketplace)
-**Motivation:** Finnancial gain, credential stuffing, spam, phishing campaigns
-**Method:** Exploited web application vulnerabilities to gain unathorized access to databases

---

### 3. Breach Overview
| Platform       | Accounts Compromised | Data exposed                               Date of Breach |
| 500px          | 14,870,304           | Email, username, MD5/SHA512 hashed passwords, PII | July 2018 |
| Dubsmash       | 161,549,210          | Email, username, SHA256 hashed passwords | Dec 2018 |
| MyFitnessPal   | 150,633.038          | Email, username, SHA1 hashed passwords, creation date | Feb 2018 |
| MyHeritage     | 92,284,478           | Email, SHA1 hashed passwords | Oct 2017 |
| EyeEm          | 22,360,765           | Email, SHA1 hashed passwords | Feb 2018 |
| 8fit           | 20,180,667           | Email, bcrypt hashed passwords, country, Facebook token | July 2018 |
| ...            | ...                  | ...                          | ...

*Full details in IOC.csv.*

---

### 4. MITRE ATT&CK Mapping
| Technique ID | Name                | Observed Use |
| T1078        | Valid Accounts      | Leaked credentials can be reused for account takeover |
| T1003        | Credential Dumping  | Password hashes (MD5/SHA1/SHA256/bcrypt) leaked |

---

### 5. Indicators of Compromise (IOCs)
See the attached ['IOCs.csv'](./IOCs.csv) for safe, redacted examples of compromised accounts.

---

### 6. Defensive Recommendations
1. **Multi-Factor Authentication:** Strongly encourage MFA on all accounts.
2. **Monitor Suspicious Login Activity:** Look for logins from unusual locations/devices.
3. **Password Hygiene:** Reset passwords and avoid reuse accross platforms.
4. **User Awareness Training:** Educate employees/customers about phishing risks.
5. **Subscribe to Threat Feeds:** HIBP, Hudson Rock, and other OSINT sources for breached accounts.

---

### 7. References
- The Register: [620 million accounts stolen, Dark web sale](https://www.theregister.com/2019/02/11/620_million_hacked_accounts_dark_web/)
- 500px Security FAQ: [500px breach announcment](https://support.500px.com/hc/en-us/articles/360011651393)
- Have I Been Pwned: [HotTopic breach details](https://haveibeenpwned.com/Breach/HotTopic)
