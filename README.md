# Cybersecurity Portfolio Index

This repository contains three defensive security labs focused on network monitoring, SIEM detection, and host-based analysis. The work was built to practise investigation workflows rather than tool installation, with each lab focusing on how evidence is collected, analysed, and interpreted during an investigation.

## Projects

- **[Network Security Monitoring (Zeek and Suricata)](https://github.com/AyrtonHCook/Network-Security-Monitoring)**  
  Analysed offline PCAP data using Zeek and Suricata to correlate DNS, LDAP, and HTTP traffic with IDS alerts and identify suspicious behaviour.

- **[Cloud Security Monitoring (Microsoft Sentinel)](https://github.com/AyrtonHCook/Microsoft-Sentinel)**  
  Onboarded Windows telemetry into Microsoft Sentinel using the Azure Monitor Agent and Data Collection Rules. Built and tested analytics to validate detection logic and alert behaviour.

- **[Windows Memory Forensics (Volatility 3)](https://github.com/AyrtonHCook/Volatility-3-project)**  
  Analysed a Windows memory dump to recover an encoded PowerShell command and reconstruct the execution context using Volatility 3.

Each project includes:
- A reproducible lab setup
- The investigation workflow and tools used 
- MITRE ATT&CK mapping where applicable
- Evidence artefacts and screenshots
- Notes on limitations and next steps

## How the labs fit together

The labs cover different stages of an investigation:
1. Network-level activity and protocol analysis  
2. Detection and alert validation in a SIEM  
3. Post-execution artefact recovery from memory  

Together, they demonstrate basic investigation capability across host, network, and cloud telemetry, aligned with junior SOC and DFIR workflows.

## Author

Ayrton Cook  
BSc Computer Science (Year in Industry)  
University of East Anglia
