# Hi, I’m Alexir 👋

I am building practical blue-team projects focused on SOC monitoring, network detection, Windows/Linux telemetry, and structured investigation writeups.

My current focus is learning by building and documenting realistic lab environments instead of only collecting notes. I use each project to practice how alerts, logs, network traffic, firewall decisions, and endpoint telemetry fit together during an investigation.

## Featured portfolio project

### Segmented SOC Monitoring and Malware Analysis Homelab

Repository: [Segmented-SOC-Monitoring-and-Malware-Analysis-Homelab](https://github.com/Alexir-Cybersec/Segmented-SOC-Monitoring-and-Malware-Analysis-Homelab)

This project is a segmented VMware-based homelab designed for SOC monitoring, controlled attack validation, and malware/PCAP analysis practice.

Current baseline includes:

- pfSense firewall segmentation across `MGMT`, `ATTACK`, `TARGET`, `DEFENSE`, `XFER`, and `ANALYSIS` networks
- Wazuh-based centralized log collection and alert review
- Windows domain telemetry from a domain controller and Windows workstation
- Sysmon, PowerShell, Windows security event, Linux auditd, nginx, and file-integrity monitoring
- Zeek and Suricata network-detection visibility through a dedicated NDR sensor
- Squid explicit proxy logging for controlled web activity visibility
- XFER-01 as a monitored SFTP transfer bridge for controlled movement of files and artifacts
- Kali and CALDERA in an isolated ATTACK segment for controlled future validation cases
- FLARE and REMnux in an ANALYSIS segment for malware and PCAP analysis workflows

The baseline documentation includes architecture diagrams, firewall-policy notes, VM inventory, screenshot evidence, validation checklists, and placeholders for future case writeups.

## Current learning focus

I am currently working on:

- SOC alert triage and investigation writeups
- Windows and Linux log analysis
- Wazuh data-source validation and alert review
- Zeek, Suricata, and proxy log correlation
- Basic detection engineering documentation
- Safe malware traffic and PCAP investigation workflows
- Building a clean public portfolio with private notes separated from publishable evidence

## Tools I am using in labs

| Area                    | Tools and technologies                                         |
| ----------------------- | -------------------------------------------------------------- |
| SIEM / monitoring       | Wazuh                                                          |
| Firewall / segmentation | pfSense                                                        |
| Network detection       | Zeek, Suricata                                                 |
| Endpoint telemetry      | Sysmon, Windows Event Logs, PowerShell logging, auditd, syslog |
| Proxy visibility        | Squid                                                          |
| Attack validation       | Kali Linux, MITRE CALDERA                                      |
| Malware / PCAP analysis | FLARE-VM and REMnux                                            |
| Virtualization          | VMware Workstation Pro 26                                      |
| Documentation           | Markdown, draw.io, GitHub                                      |

## Portfolio roadmap

Current status:

- Completed and documented the baseline segmented SOC homelab
- Captured screenshot evidence for major systems and data sources
- Created architecture, telemetry, file-transfer, and attack-to-detection diagrams

Next planned work:

- Internal SOC case writeups such as failed logon triage and suspicious PowerShell review
- Kali-generated validation cases against selected lab targets
- CALDERA-generated adversary-emulation cases
- Malware-traffic-analysis style PCAP investigation writeups

## How I document projects

I try to keep public documentation honest and evidence-based:

- I document what was actually built and verified
- I avoid uploading secrets, private keys, raw malware samples, or unsafe archives
- I separate private study notes from public portfolio writeups
- I use screenshots, diagrams, and validation checklists to make projects easier to review

## Contact & Credentials

- **LinkedIn:** https://www.linkedin.com/in/aicbarrios
- **Credly (CCNA Verification):** https://www.credly.com/users/aicbarrios
- **Portfolio Project:** [Segmented SOC Monitoring and Malware Analysis Homelab](https://github.com/Alexir-Cybersec/Segmented-SOC-Monitoring-and-Malware-Analysis-Homelab)
- **Email:** ece.aibarrios@gmail.com

---

This profile is a work in progress as I continue building case writeups and improving my blue-team portfolio.
