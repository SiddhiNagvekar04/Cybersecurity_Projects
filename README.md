# Cybersecurity Log Analysis (SOC Beginner Project)

This project demonstrates a beginner-friendly Security Operations Center (SOC) investigation by analyzing authentication logs to detect suspicious login behavior, brute-force attempts, credential stuffing, and possible account compromise.  
The goal is to understand how real SOC teams identify and report threats using log data.

---

## 🔍 Project Overview

- Analyzed **30+ authentication log entries**  
- Identified **5+ major security anomalies**
- Detected brute-force attempts, foreign login anomalies, and multi-user targeting  
- Created a structured SOC-style incident report with findings and recommendations  
- Project built without coding using online log viewers and sample SIEM logs

---

## 📁 Files Included

### **1. Cybersecurity_Log_Analysis_Project.pdf**
A complete SOC-style analysis including:
- Summary of authentication logs  
- Suspicious activity detection  
- Quantitative findings  
- Threat patterns  
- Recommendations  
- Final conclusion

### **2. Sample Log File (Included inside PDF)**
Custom-generated set of authentication logs used for analysis.

---

## 🧠 Key Findings

- **12 failed login attempts** across **4 accounts** from one malicious IP  
- **3 rapid failed attempts** on user *alex* indicating brute-force  
- **Foreign login (Russia)** for user *priya_p* → suspicious success  
- **2 account lockouts** due to repeated failures  
- **Credential stuffing attempt** targeting multiple user accounts  

---

## 🛡 Recommendations

- Enable Multi-Factor Authentication (MFA)  
- Block malicious/suspicious IPs  
- Implement brute-force alerting rules  
- Enforce password reset on impacted accounts  
- Add geolocation-based login alerts  

---

## 📚 Skills Demonstrated

- Log reading and interpretation  
- Identifying brute-force patterns  
- Recognizing compromised login behavior  
- SOC incident reporting  
- Basic SIEM concepts  
- Documentation and report writing  

---

## 🧰 Tools Used

- Online Log Viewer  
- Sample SIEM Logs  
- ReportLab (for PDF generation)  
- Google Docs (for documentation)  

---

## 📌 About This Project

This project was created as part of cybersecurity internship preparation to demonstrate beginner SOC analyst skills.  
It reflects real-world tasks performed by Tier-1 SOC analysts such as monitoring logs, analyzing events, and detecting anomalies.

---

## 🤝 Contributions

If you would like to suggest improvements, feel free to open an issue or submit a pull request.

---

## 📬 Contact
For queries or collaborations, feel free to reach out via GitHub or LinkedIn.
