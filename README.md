# Vulnerability Assessment Report

## Cyber Security Internship | Future Interns 2026

---

## Overview

This project presents a passive vulnerability assessment of a public web application (OWASP Juice Shop), conducted as part of the Future Interns Cyber Security Internship 2026.

The assessment was strictly non-intrusive, focusing on identifying security misconfigurations without exploitation.

---

## Scope

- **Target:** juice-shop.herokuapp.com  
- **Environment:** Public demo application (AWS-hosted)  
- **Methodology:** Passive / Read-only scanning  
  

---

## Tools

- **SecurityHeaders.com** —> HTTP security headers analysis  
- **SSL Labs (Qualys)** —> SSL/TLS configuration testing  
- **Mozilla Observatory** —> Security posture evaluation  

---

## Key Findings

- Missing critical security headers (HSTS, CSP) —> **High Risk**  
- No enforced HTTPS redirection —> **High Risk**  
- Multiple missing policy headers —> **Medium Risk**  
- SSL configuration requires optimization —> **Medium Risk**  

---

## Security Ratings

- **Security Headers:** D  
- **SSL Labs:** A-  
- **Mozilla Observatory:** 35/100 (D)  

---

## Repository Structure

- `README.md` — Project summary  
- `Vulnerability_Assessment_Report.pdf` — Detailed report  
- `screenshots/` — Supporting evidence  

---

## Ethics & Compliance

- Passive testing only  
- No exploitation performed  
- No authentication or brute-force attempts  
- Publicly accessible resources only  

---

## Internship Context

- **Program:** Future Interns Cyber Security Internship  
- **Track:** Cyber Security (CS)  
- **Task:** Vulnerability Assessment Report  
- **Repository:** FUTURE_CS_01  

---

**LinkedIn:** https://tz.linkedin.com/in/faridi-hant-60b06b344  
**Organization:** https://www.linkedin.com/company/future-interns/

---

> **Note:** This assessment was conducted in accordance with ethical security testing standards.
