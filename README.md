#Phishing Threat Analysis & MITRE ATT&CK Mapping

## Overview
This project simulates a real-world SOC triage workflow by investigating live phishing URLs, 
identifying attacker techniques, and producing a MITRE ATT&CK-mapped threat report with 
mitigation recommendations.

## Objectives
- Investigate active phishing infrastructure using open-source threat intelligence tools
- Identify attacker deception techniques used to bypass enterprise email filters
- Map findings to the MITRE ATT&CK framework and produce analyst-ready deliverables

## Tools & Resources
| Tool | Purpose |
|------|---------|
| [PhishTank](https://phishtank.org) | Live phishing URL database for investigation |
| [VirusTotal](https://virustotal.com) | Malicious infrastructure analysis & URL scanning |
| MITRE ATT&CK Navigator | Technique mapping and visualization |

## Methodology
1. **URL Collection** – Sourced active phishing URLs from PhishTank
2. **Infrastructure Analysis** – Used VirusTotal to trace domains, IPs, and hosting patterns
3. **Technique Identification** – Identified deception methods including:
   - Brand impersonation
   - Typosquatting
   - URL obfuscation
4. **ATT&CK Mapping** – Mapped attacker behaviors to relevant MITRE ATT&CK tactics and techniques
5. **Reporting** – Compiled findings into a prioritized threat report with mitigation recommendations

## MITRE ATT&CK Techniques Identified
| Technique ID | Name | Tactic |
|-------------|------|--------|
| T1566.002 | Spearphishing Link | Initial Access |
| T1036 | Masquerading | Defense Evasion |
| *(add more as applicable)* | | |

## Key Findings
- *(Summarize 2–3 notable patterns or attacker behaviors you uncovered)*

## Mitigation Recommendations
- *(List your top recommendations, e.g., email filtering rules, user awareness training, domain monitoring)*

## Author
**Dhru** | Cybersecurity Analytics and Operations, PSU  
www.linkedin.com/in/dhrupatel06

---
*This project was completed as part of an academic exercise in cybersecurity threat analysis.*
