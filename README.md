# dfir-web-attack-investigation

This repository contains a Digital Forensics and Incident Response (DFIR) case study based on the **LetsDefend Blue Team Challenge: Investigate Web Attack**.  
The goal of this project was to analyze real Apache access logs, trace an attacker’s activity, and document the full investigation and response process.

## Project Overview
- **Platform:** LetsDefend (Blue Team Challenge)  
- **Case Study:** Investigate Web Attack  
- **Focus:** Log analysis, incident investigation, and attack chain reconstruction  
- **Author:** Harikumar Nandakumar  

## Key Findings
The investigation revealed multiple attacker techniques:
1. **Reconnaissance** – Automated scanning (Nikto) detected.  
2. **Enumeration** – Directory brute forcing for hidden/sensitive files.  
3. **Credential Access** – Brute force login attempts leading to successful access.  
4. **Execution** – Command injection to run OS-level commands.  
5. **Persistence** – Creation of a new local account for long-term access.  

## Defensive Takeaways
- Detect and block automated scanning and brute force activity.  
- Enforce MFA and brute force protections on login portals.  
- Apply strict input validation to prevent command injection.  
- Monitor and alert on suspicious account creation events.  

## Repository Contents
- **Investigate Web Attack.pdf** – Full investigation report.  
- **README.md** – Summary of the case study.  

---

### About
This project demonstrates practical **SOC analyst and DFIR skills** by investigating a simulated real-world web attack, showcasing the ability to detect, analyze, and respond to incidents.
