# Incident Report

## Time of Activity
05/25/2026 02:35:02.320

---

## Affected Entities
- Source Host: 10.20.2.17
- Destination IP: 67.199.248.11
- URL: http://bit.ly/3sHkX3da12340

---

## Analysis Summary
The alert was triggered due to an attempted connection to a blacklisted URL associated with a URL shortening service commonly used in phishing campaigns.

Threat intelligence (VirusTotal: 1/92 vendors) indicates low-confidence malicious classification.

No evidence of execution or compromise was identified.

---

## Final Classification
Low severity — blocked suspicious web access attempt

---

## Supporting Observations
- Connection blocked by firewall
- No endpoint execution detected
- No persistence or lateral movement observed
