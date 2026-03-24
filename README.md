# FICBANK Security Monitoring & Log Analysis

## Project Files
- [Security Assessment Report](https://github.com/Viney-Washington/ficbank-security-monitoring-analysis/blob/main/Viney%20Washington%20_%20%20FICBANK-Security-Monitoring-Assessment.pdf)
- [Security Monitoring Data Analysis](https://github.com/Viney-Washington/FICBANK-Security-Monitoring-Data-Analysis/blob/main/FICBANK-Security-Monitoring-Data-Analysis.pdf)

## Overview
This project analyzes FICBANK web server logs (Access and Apache logs) using PowerShell to identify suspicious activity, detect potential threats, and evaluate the effectiveness of security monitoring controls.

## Key Skills Demonstrated
- Log Analysis (Apache, Access Logs)
- PowerShell Data Analysis
- Threat Detection & Monitoring
- Network Traffic Analysis
- Security Assessment & Reporting

## Key Findings
- Identified over 1,700 unique IP addresses interacting with the system
- Detected repeated HTTP 400 and 404 errors indicating malformed or failed requests
- Observed HTTP tunneling attempts (CONNECT requests)
- Detected Shellshock exploit attempts (CVE-2014-6271)
- Identified automated bot activity (Googlebot and scanning behavior)

## Tools Used
- Windows PowerShell
- Log File Analysis
- Manual Threat Investigation

## Recommendations
- Implement Web Application Firewall (WAF) to block malicious requests
- Apply patches to mitigate known vulnerabilities such as Shellshock
- Monitor and restrict abnormal CONNECT requests to prevent tunneling
- Strengthen logging and alerting for HTTP errors and suspicious IP activity
- Implement intrusion detection/prevention systems (IDS/IPS) for real-time monitoring
