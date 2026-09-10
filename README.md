# 🔐 Web Application Penetration Testing – Week 4 Capstone

## 👨‍💻 About the Project

This project was completed as part of the **Networkwalks B082 – Week 4 Cybersecurity Internship Capstone Project**.

**Prepared by:** T Durga Bharadwaj  
**Organisation:** Networkwalks  
**Project:** Web Application Penetration Testing  
**Target:** Mediroza General Hospital training environment  
**Testing Type:** Black-Box Penetration Testing  

> ⚠️ This project was performed as part of an authorised educational security assessment. The techniques demonstrated here must only be used on systems for which explicit permission has been provided.

---

## 🎯 Objective

The objective was to assess the security of a web application, identify vulnerabilities, demonstrate their impact in a controlled environment, and recommend appropriate remediation.

The assessment followed four major stages:

1. Reconnaissance
2. Vulnerability Identification
3. Controlled Exploitation
4. Documentation & Remediation

---

## 🔍 Security Findings

During the assessment, the following vulnerabilities were identified:

| # | Finding | Severity |
|---|---------|----------|
| 1 | Username Enumeration | 🟡 Medium |
| 2 | SQL Injection / Authentication Weakness | 🔴 Critical |
| 3 | Exposure of Confidential Patient Reports | 🟠 High |
| 4 | Weak PDF Password Protection | 🟠 High |
| 5 | Sensitive PDF Metadata Exposure | 🟡 Medium |
| 6 | Directory Listing / Exposed Paths | 🔴 Critical |
| 7 | Sensitive Database Backup Exposure | 🔴 Critical |

**Overall Risk Rating: 🔴 CRITICAL**

---

## 🧰 Tools Used

- Kali Linux
- curl
- Web Browser
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- PDF Viewer
- qpdf
- exiftool
- wget

---

## 🔗 Attack Chain

The assessment demonstrated how several individual security weaknesses could be combined into a larger attack chain.

**Reconnaissance**
⬇️  
**Information Disclosure**
⬇️  
**Authentication Weakness**
⬇️  
**SQL Injection**
⬇️  
**Patient Report Exposure**
⬇️  
**Weak PDF Protection**
⬇️  
**Sensitive Information Exposure**
⬇️  
**Database Backup Exposure**

This project helped me understand why penetration testing should focus not only on individual vulnerabilities but also on how vulnerabilities can be chained together.

---

## 🛡️ Recommended Remediation

Key recommendations include:

- Use generic authentication error messages.
- Implement parameterised queries / prepared statements.
- Disable detailed database errors in production.
- Enforce server-side access control for sensitive files.
- Store confidential reports outside the public web root.
- Use strong and unique passwords where document encryption is required.
- Remove unnecessary PDF metadata.
- Disable directory listing.
- Never store database backups in publicly accessible directories.
- Implement security logging and monitoring.

---

## 📚 Key Learnings

Through this project, I gained practical understanding of:

- Web reconnaissance
- Authentication testing
- Username enumeration
- SQL injection concepts
- Access-control weaknesses
- Password security
- PDF hash extraction
- Dictionary attacks
- Metadata analysis
- Directory exposure
- Sensitive-data exposure
- Vulnerability chaining
- Risk classification
- Security remediation
- Professional penetration-testing documentation

---

## 📄 Penetration Testing Report

A detailed penetration-testing report was prepared containing:

- Executive Summary
- Scope & Methodology
- Findings
- Risk Ratings
- Redacted Evidence Screenshots
- Attack Chain
- Remediation Recommendations
- Conclusion

Sensitive information in screenshots has been redacted before documentation.

---

## ⚖️ Ethical Disclaimer

This repository documents an **authorised educational cybersecurity exercise**.

Never perform penetration testing, password attacks, SQL injection, or other security testing against systems without explicit authorisation from the system owner.

---

## 👨‍💻 Author

**T Durga Bharadwaj**

Cybersecurity Learner | SOC Analyst Aspirant

### Networkwalks B082
**Week 4 – Capstone Project**
