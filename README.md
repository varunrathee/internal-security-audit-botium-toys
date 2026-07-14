# 🛡️ Internal Security Audit – Botium Toys

Internal cybersecurity audit for a fictional toy company, evaluating security 
controls and compliance readiness against NIST CSF, PCI DSS, GDPR, and SOC 
frameworks.

---

## 📌 Project Overview
This project documents an internal security audit conducted for a fictional 
organization, Botium Toys. The audit evaluates existing security controls, 
identifies risks, and provides recommendations aligned with industry-standard 
cybersecurity frameworks. Based on the Google Cybersecurity Certificate's 
"Conduct a Security Audit" portfolio activity, extended with independent 
analysis and documentation.

## 🔑 Key Findings
- **Overall Risk Score: 8/10 (High Risk)**
- No encryption for sensitive customer data at rest or in transit
- No least-privilege access control — all employees can access sensitive data
- No formal disaster recovery or backup plan in place
- Missing intrusion detection capabilities
- **PCI DSS status: Not compliant** — no cardholder data restrictions or encryption in place

## ✅ Controls Assessment Summary

**Administrative Controls**
| Control | Status | Justification |
|---|---|---|
| Least Privilege | ❌ No | All employees have access to internally stored data, including sensitive information |
| Separation of Duties | ❌ No | No role-based access controls have been implemented |
| Password Policy | ❌ No | Policy exists but does not meet minimum complexity standards |
| Disaster Recovery Plan | ❌ No | No formal disaster recovery plans are in place |

**Technical Controls**
| Control | Status | Justification |
|---|---|---|
| Firewall | ✅ Yes | Implemented and configured with security rules |
| Intrusion Detection System (IDS) | ❌ No | IDS has not been installed |
| Encryption | ❌ No | Customer credit card data is not encrypted |
| Antivirus Software | ✅ Yes | Installed and monitored |
| Backups | ❌ No | No backups of critical data exist |
| Password Management System | ❌ No | No centralized password management solution |

**Physical Controls**
| Control | Status | Justification |
|---|---|---|
| Locks (Office/Warehouse) | ✅ Yes | Physical locks are present |
| CCTV Surveillance | ✅ Yes | Installed and operational |
| Fire Detection & Prevention | ✅ Yes | Alarms and prevention systems are in place |

📌 **Summary:** Botium Toys has basic physical and limited technical controls in 
place. However, critical administrative and technical controls are missing, 
significantly increasing overall organizational risk.

## 🎯 Objectives
- Assess internal security posture
- Identify gaps in security controls
- Evaluate compliance readiness
- Recommend risk mitigation strategies

## 🧰 Frameworks & Standards Used
- NIST Cybersecurity Framework (CSF)
- PCI DSS
- GDPR
- SOC (Security Operations Controls)

## 📂 Project Structure
| Folder | Contents |
|---|---|
| [`audit/`](./audit) | Controls assessment, compliance assessment, risk summary, recommendations |
| [`frameworks/`](./frameworks) | Framework-specific mapping docs (NIST CSF, PCI DSS, GDPR, SOC) |
| [`docs/`](./docs) | Source scope/goals/risk assessment report and checklists |
| [`resume/`](./resume) | Resume bullet points and skills demonstrated |

## 🛠️ Sample Recommendations
- Implement least privilege access controls and role-based access policies
- Encrypt customer and payment data at rest and in transit
- Establish a formal disaster recovery and backup plan
- Deploy intrusion detection and continuous monitoring capabilities

## 👤 Author
Varun Rathee | BCA | Cybersecurity Enthusiast

## ⚠️ Disclaimer
This project is for educational and portfolio purposes only.
