# soc-incident-case-study-Phishing1

## Overview
This project simulates a real SOC Level 1 investigation using SIEM (Splunk) to analyze a blocked access attempt to a potentially malicious URL.

## Scenario
A user attempted to access a shortened URL (Bitly) flagged by threat intelligence systems and blocked by firewall controls.

## Tools Used
- Splunk (SIEM)
- Firewall logs
- Threat Intelligence (VirusTotal-style analysis)

## Outcome
- No compromise detected
- Access was blocked at perimeter
- Classified as low severity true positive detection (Blocked Attempt / No Compromise)

## Skills Demonstrated
- SIEM log analysis
- Threat intelligence correlation
- IOC extraction
- Incident classification
- SOC reporting
