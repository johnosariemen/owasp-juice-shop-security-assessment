# OWASP Juice Shop Security Assessment

## Project Overview

A hands on web application security assessment of **OWASP Juice Shop** performed in a controlled local laboratory environment.

The assessment focused on reconnaissance, API enumeration, vulnerability testing, authentication and authorization testing, source-code review, evidence collection, and security remediation recommendations.

## Objectives

* Perform reconnaissance and information gathering
* Identify the application's attack surface
* Test selected web application security controls
* Review relevant application source code
* Collect evidence of security findings
* Assess the potential impact of identified issues
* Provide practical remediation recommendations

## Testing Environment

* **Target:** OWASP Juice Shop 20.2.0
* **Environment:** Local Docker laboratory
* **Operating System:** Kali Linux
* **Browser:** Firefox
* **Assessment Type:** Authorized security assessment

## Tools Used

* Kali Linux
* Docker
* WhatWeb
* cURL
* Firefox Developer Tools
* Node.js / JavaScript utilities
* Linux command-line tools
* Source-code review

## Assessment Activities

The assessment included:

* HTTP response and security header analysis
* Application reconnaissance
* API endpoint enumeration
* Authentication and authorization testing
* SQL injection testing
* SSRF testing
* BOLA/IDOR testing
* Source-code analysis
* Evidence collection and documentation

## Confirmed Findings

The assessment confirmed six security findings:

1. **SQL Injection — Product Search**
2. **SQL Injection — Login**
3. **Sensitive Information Exposure in JWT**
4. **Broken Function-Level Authorization & Excessive User Data Exposure**
5. **Server-Side Request Forgery (SSRF)**
6. **Broken Object Level Authorization (BOLA/IDOR)**

Detailed technical findings, evidence, impact, classifications, and remediation recommendations are documented in the full assessment report.

## Evidence

Supporting screenshots and evidence are organized by assessment area:

- [Reconnaissance](./screenshots/reconnaissance/)
- [SQL Injection](./screenshots/sql-injection/)
- [Authorization](./screenshots/authorization/)
- [SSRF](./screenshots/ssrf/)
- [BOLA/IDOR](./screenshots/bola-idor/)

## Full Report

[**View the OWASP Juice Shop Security Assessment Report**](./OWASP-Juice-Shop-Security-Assessment.pdf)

## Disclaimer

This assessment was performed against a deliberately vulnerable application in a controlled local laboratory environment for educational and cybersecurity training purposes.

No production systems or unrelated external systems were targeted.
