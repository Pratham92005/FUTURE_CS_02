
# Security Log Analysis Report

This project contains a **security incident analysis report** generated using **Splunk SIEM**. The investigation focused on suspicious activities detected in authentication logs, network traffic, firewall logs, and malware alerts.

### 🔍 Key Findings

* **Failed Login Attempts**: Multiple failed logins, indicating possible brute-force attempts.
* **Network Traffic**: Suspicious outbound connections suggesting potential data exfiltration.
* **Firewall Logs**: Blocked scanning attempts on SSH, RDP, and HTTP ports.
* **Malware Alerts**: Trojan (Redline) detected and quarantined to prevent credential theft.

### ⚠️ Impact & Risks

* Unauthorized access attempts → High risk of account compromise.
* Suspicious traffic → Medium–High risk of data exfiltration.
* Firewall probing → Medium risk of exploitation.
* Active malware → High risk to data integrity and system security.

### ✅ Recommendations

* Enforce strong password & lockout policies.
* Block malicious IPs & monitor outbound traffic.
* Harden firewall rules & apply geo-blocking.
* Isolate infected hosts, update antivirus, and patch systems.


