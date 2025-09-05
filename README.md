# BazTech-Inc.-SOC-Implementation-and-Threat-Simulation.
This project documents the design, implementation, and testing pf a simulated Security Operations Center (SOC) for BazTech Inc., a growing tech startup focused on IT and data security.

## Overview.  
The SOC environment was built to address gaps in network visibility ,log centralization, and incident correlation across segmented infrastructure. Using pfsense for network segmentation and wazuh for centralized mornintoring, the project tested defenses with a controlled black-hat attack simulation.

## Key Achievements.
    . Designed and deployed four network segments: WAN, IT Department, LAN, AND DMZ.
    . Installed and configured Wazuh Manager and agents for real-time log analysis.
    . Conduted simulated insider attack using Nmap and Hydra to identify vulnerabilities.
    . Detected credential harvesting, brute-force attemps and lateral movement through SOC monitoring.
    . Mapped alerts to MITRE ATT&CK techniques and compliance frameworks (PCI DSS, NIST800-53, TrustService Criteria).

## Findings 
     . SNMP service exposed to unauthorized segments
     . Weak password policies enabled successful brute-force attacks.
     . No automatic IP blocking or rate limiting on SSH.

## Recommendations.
     . Harden VLAN access control and inter-segment ACLs.
     . Restrict ricky services like SSH and SNMP to trusted IPs only.
     . Deploy IDS/IPS with behavioral analytics.
     . Enforce MFA and strong password policies.
     . Automate detection and blocking of malicious IPs 
     
## Impact 
This SOC simulation revealed real security weakness and provided a clear path towords building a robust, real-word SOC capable of detecting and morning advanced threats.

## Report.
[Report](https://github.com/osehale/BazTech-Inc.-SOC-Implementation-and-Threat-Simulation./blob/main/Philip%20U%20fuah_SOC_Project.Pdf)

