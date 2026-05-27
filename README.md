# FUTURE_CS_01
# Vulnerability Assessment Report

## Objective
Performed a vulnerability assessment on the OWASP Juice Shop demo application using Nmap and OWASP ZAP.

## Tools Used
- Nmap
- OWASP ZAP
- Kali Linux (WSL)
- GitHub

## Activities Performed
- Port scanning
- Service detection
- Vulnerability analysis
- Risk identification

## Scan Target
https://demo.owasp-juice.shop

## Nmap Scan Results
The scan identified multiple open ports including:
- FTP (21)
- HTTP (80)
- HTTPS (443)
- HTTP Proxy (8080)

Some ports were filtered, indicating firewall protection mechanisms.

## OWASP ZAP Findings

The OWASP ZAP automated scan detected multiple security-related findings including:

- Content Security Policy (CSP) Header Not Set
- Cross-Domain Misconfiguration
- Server Information Disclosure
- Timestamp Disclosure

These findings demonstrate common web application security weaknesses and configuration issues.

## Skills Learned
- Vulnerability Assessment
- Web Security Testing
- Reconnaissance
- Security Documentation
- GitHub Project Management

## Screenshots
Project screenshots are available in the repository.

## Conclusion
This project helped in understanding the basics of reconnaissance, vulnerability assessment, and web application security testing.
