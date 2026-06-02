# Web-Penetration-Testing

----------------------------------------------------------------------------------------------------
# Altoro Mutual Web Application VAPT Report

## Overview

This repository contains a Web Application Vulnerability Assessment and Penetration Testing (VAPT) report conducted against the Altoro Mutual demo banking application (`demo.testfire.net`).

The assessment was performed to identify security weaknesses, evaluate their potential impact, and provide remediation recommendations based on industry best practices and OWASP guidelines.

## Project Information

* **Target Application:** Altoro Mutual Banking Application
* **Target URL:** http://demo.testfire.net
* **Assessment Type:** Web Application Penetration Testing
* **Testing Period:** 23 April 2026 – 26 April 2026
* **Auditor:** Hrushikesh Sanjay Nehete
* **Tools Used:** Burp Suite Professional, Nmap, Nikto, Nessus, GitHub

## Scope

The assessment focused on:

* Authentication Mechanisms
* Session Management
* Input Validation
* Access Control
* Business Logic Controls
* Security Headers
* Data Exposure Risks
* Application Configuration

## Key Vulnerabilities Identified

### Critical Vulnerabilities

* SQL Injection (Authentication Bypass)
* SQL Injection (Search Functionality)
* Reflected Cross-Site Scripting (XSS)
* Stored Cross-Site Scripting (XSS)

### High Severity Vulnerabilities

* Insecure Direct Object Reference (IDOR)
* Parameter Tampering
* Business Logic Flaw
* Credentials Transmitted in Plain Text
* Default Credentials Enabled

### Medium Severity Vulnerabilities

* Weak Password Policy
* Missing Account Lockout Mechanism
* Missing Anti-CSRF Protection
* Information Disclosure
* Clickjacking Vulnerability
* Content Spoofing
* Improper Error Handling
* Version Disclosure

## Risk Summary

| Severity | Count |
| -------- | ----- |
| Critical | 4     |
| High     | 5     |
| Medium   | 8     |
| Low      | 3     |

## Testing Methodology

1. Information Gathering
2. Automated Scanning
3. Manual Verification
4. Vulnerability Validation
5. Risk Assessment
6. Remediation Recommendations

## Skills Demonstrated

* Web Application Penetration Testing
* Manual Security Testing
* Burp Suite Professional
* SQL Injection Testing
* Cross-Site Scripting Assessment
* Authentication Testing
* Access Control Testing
* OWASP Top 10 Mapping
* Vulnerability Reporting

## Disclaimer

This assessment was conducted against a deliberately vulnerable training application for educational and professional skill development purposes only. No unauthorized testing was performed against production systems.

## Author

**Hrushikesh Sanjay Nehete**
Cyber Security Analyst | Web Application Penetration Tester

----------------------------------------------------------------------------------------------------
# Gin & Juice Shop Web Application VAPT Report

## Overview

This repository contains a comprehensive Web Application Vulnerability Assessment and Penetration Testing (VAPT) report conducted against the Gin & Juice Shop e-commerce platform.

The objective of the assessment was to identify security weaknesses, validate exploitability, and provide remediation recommendations aligned with OWASP and industry security standards.

## Project Information

* **Target Application:** Gin & Juice Shop
* **Target URL:** https://ginandjuice.shop
* **Assessment Type:** Web Application Penetration Testing
* **Testing Period:** 09 May 2026 – 10 May 2026
* **Auditor:** Hrushikesh Sanjay Nehete
* **Tools Used:** Burp Suite Professional, Nessus, Nmap, Nikto, GitHub

## Scope

The assessment included:

* Authentication Controls
* Session Management
* Input Validation
* SQL Injection Testing
* Security Header Analysis
* Information Disclosure Testing
* Application Configuration Review
* Business Logic Validation

## Key Vulnerabilities Identified

### Critical Vulnerabilities

* SQL Injection in Search Parameter
* Boolean-Based Blind SQL Injection

### High Severity Vulnerabilities

* Credentials Transmitted in Plain Text
* Default Credentials Used for Authentication
* AngularJS Version Disclosure

### Medium Severity Vulnerabilities

* Multiple Active Session Vulnerability
* Missing Content Security Policy (CSP)
* Missing Referrer Policy Header
* Improper Input Validation

### Low Severity Vulnerabilities

* XML Version Disclosure

## Risk Summary

| Severity | Count |
| -------- | ----- |
| Critical | 2     |
| High     | 3     |
| Medium   | 4     |
| Low      | 1     |

## Security Testing Methodology

### Reconnaissance

* Application Mapping
* Endpoint Enumeration
* Technology Identification

### Vulnerability Assessment

* Automated Security Scanning
* Manual Verification
* False Positive Elimination

### Penetration Testing

* Injection Testing
* Session Management Testing
* Authentication Testing
* Security Misconfiguration Review

### Reporting

* Vulnerability Documentation
* Risk Classification
* Remediation Guidance

## Skills Demonstrated

* Web Application Security Testing
* Burp Suite Professional
* SQL Injection Detection
* Session Management Assessment
* Security Header Analysis
* Vulnerability Validation
* Risk Assessment
* Technical Report Writing
* OWASP Top 10 Testing

## Key Learning Outcomes

* Identification of Injection Vulnerabilities
* Secure Authentication Assessment
* Session Security Analysis
* Secure Configuration Review
* Vulnerability Prioritization
* Professional VAPT Reporting

## Disclaimer

Testing activities were conducted in accordance with authorized security assessment practices and are documented solely for educational, professional development, and portfolio purposes.

## Author

**Hrushikesh Sanjay Nehete**
Cyber Security Analyst | Web Application Penetration Tester

----------------------------------------------------------------------------------------------------
