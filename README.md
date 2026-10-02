# OWASP Juice Shop Security Assessment

## Project Overview

A hands on web application security assessment of OWASP Juice Shop performed in a controlled local lab environment.

The assessment focused on reconnaissance, enumeration, attack-surface identification, vulnerability testing, source-code review, evidence collection, and security remediation recommendations.

## Objectives

- Perform reconnaissance and information gathering
- Identify the application's attack surface
- Test selected web application security controls
- Review relevant application source code
- Collect evidence of security findings
- Assess the potential security impact of identified issues
- Provide practical remediation recommendations

## Testing Environment

- **Target:** OWASP Juice Shop
- **Environment:** Local Docker lab
- **Operating System:** Kali Linux
- **Application URL:** `http://127.0.0.1:3000`
- **Assessment Type:** Authorized security assessment

## Tools Used

- WhatWeb
- cURL
- Docker
- Kali Linux
- Browser Developer Tools
- Source-code review
- Linux command-line tools

## Assessment Activities

The assessment included:

- HTTP response and security header analysis
- Application reconnaissance
- Endpoint enumeration
- Administrative endpoint review
- Application configuration review
- Source-code analysis
- SSRF-related testing
- Authentication and session-related observations
- Evidence collection and documentation

## Key Findings

The assessment identified security-relevant observations involving:

- Application information exposure
- Administrative configuration exposure
- Server-side request behavior
- Authentication and session handling
- Application source-code and endpoint analysis

Detailed technical findings, evidence, impact, and remediation recommendations are documented in the full assessment report.

## Evidence

Screenshots, command outputs, and other supporting evidence were collected during the assessment and are included in the project documentation.

## Remediation

Recommendations are provided for each identified security issue, including appropriate access controls, input validation, secure configuration, authentication controls, and reduction of unnecessary information exposure.

## Full Report

The complete security assessment report is available here:

[OWASP Juice Shop Security Assessment Report](./OWASP-Juice-Shop-Security-Assessment.pdf)

## Disclaimer

This assessment was performed against a deliberately vulnerable application in a controlled local lab environment for educational and cybersecurity training purposes.
