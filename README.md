## Hi there 👋

# Ademola Durodola

> *IT Support Professional | Aspiring Blue Team Analyst*
> *Alexandria, VA · Open to Remote & Hybrid*

---

## About Me

I am a current retail store manager transitioning into cybersecurity while completing my B.S. in Information Technology at UMGC. Managing people and operations under pressure has taught me how to communicate clearly, solve problems methodically, and stay calm when things break, skills I apply daily in my homelab. I believe education is the best legacy, a principle I carried from Nigeria and have never let go. I do not know everything and never will, but I am committed to never stopping learning.

---

## Education & Certifications

| | | | |
|---|---|---|---|
| 🎓 **B.S. Information Technology — Cybersecurity** | University of Maryland Global Campus (UMGC) | Graduating Summer 2026 | |
| ✅ **CompTIA A+** | CompTIA | Earned | [Verify →](https://www.credly.com/badges/21de2c15-9f36-4e4a-9167-53f8e523ab83) |
| ✅ **CompTIA Network+** | CompTIA | Earned | [Verify →](https://www.credly.com/badges/21de2c15-9f36-4e4a-9167-53f8e523ab83) |
| ✅ **Google IT Automation with Python** | Google / Coursera | In Progress 
| 🟡 **CompTIA Security+** | CompTIA | In Progress (50%) | — |

---

## Projects

### 🎫 HERMES — Helpdesk Ticketing & Automation
**[View Repository →](https://github.com/AdemolaTech23/HERMES---Helpdesk-Ticketing-and-Automation)**

Simulated helpdesk environment built on Windows Server 2022 with osTicket, Active Directory, and PowerShell automation. Five real ticket scenarios documented end-to-end with screenshots, scripts, and user confirmations.

| Ticket | Scenario | Key Skills |
|---|---|---|
| T001 | Password Reset | ADUC, secure credential handling, ticket lifecycle |
| T002 | Account Lockout | Get-ADUser, Unlock-ADAccount.ps1, GPO lockout policy |
| T003 | New User Onboarding (15 users, 4 departments) | AD provisioning scripts, OU structure, security groups |
| T004 | Network Share Access — "Path Not Found" | DNS root cause, SMB diagnostics, NTFS permissions |
| T005 | GPO PowerShell Execution Policy | Group Policy, AllSigned enforcement, MITRE T1059.001 |

---

### 🔐 ARGUS — Homelab SOC Automated Pipeline
**[View Repository →](https://github.com/AdemolaTech23/ARGUS---Homelab-SOC-Automated-Pipeline)**

Enterprise-style SOC lab built from scratch on Proxmox. Phase 1 complete — Wazuh SIEM deployed, Sysmon telemetry configured, SMB brute force simulated via CrackMapExec, 3,977 EID 4625 events detected, false positive investigated and tuned. Phases 2–5 cover SOAR automation, Splunk, Elastic, and full network segmentation via pfSense.

---

### 🖥️ osTicket — Helpdesk Deployment with AD Authentication
**[View Repository →](https://github.com/AdemolaTech23/osTicket-Help-Desk-Deployment-with-Active-Directory-Authentication)**

Full osTicket deployment on Ubuntu 24.04, integrated with Windows Server 2022 Active Directory for domain-based authentication. Foundation platform used across all HERMES ticket simulations.

---

## Experience

### Store Manager — Hollister Co.
*June 2023 – Present*

- Currently leading daily store operations, staff scheduling, and performance management for a team of [X] employees
- Resolve customer escalations and complex issues under pressure — directly transferable to IT support ticket triage and end-user communication
- Maintain accountability for inventory, compliance, and operational documentation — mirrors the discipline required for IT change management and incident logging
- <!-- TODO: Add 1–2 more bullets if relevant -->


---

## Hands-On Lab Training — uCertify

CompTIA A+ and Network+ coursework completed via uCertify with **40+ hands-on virtual labs** at 100% completion across all core exam domains.

**Hardware, Storage & Peripherals**
![uCertify Labs — Hardware and Peripherals] <img width="1229" height="758" alt="image" src="https://github.com/user-attachments/assets/206ae3c4-d800-4836-ad75-16bc6f863a29" />


> Installing memory modules, verifying RAM, drive letters, FAT32→NTFS conversion, dynamic disks, storage pools, optical drives, printers (install/share/USB/ink), mobile devices (iOS & Android), laptop components

---

**Core Hardware & Motherboard Assembly**
![uCertify Labs — Core Hardware] <img width="1379" height="755" alt="image" src="https://github.com/user-attachments/assets/c6827d7d-69bb-408e-a050-6f4094d51b83" />


> Device drivers, USB/hub connections, PCI cards, hardware virtualization, CPU socket, processor installation, expansion cards, SATA power, motherboard assembly, BIOS, NIC installation, full PC assembly, power supply replacement

---

**Networking, OS & Scripting**
![uCertify Labs — Networking and OS] <img width="1227" height="839" alt="image" src="https://github.com/user-attachments/assets/76d6080b-fdb5-4f8c-b176-dd81b096547d" />


> VPN setup, IPv4/IPv6 configuration, DNS, DHCP, VLAN creation, network diagnostics (ping, tracert, nslookup, ipconfig, net), EFS file sharing, Windows Registry, Command Prompt, PowerShell scripting

---

| Domain | Status |
|---|---|
| Hardware — PC Assembly & Components | ✅ |
| Hardware — Storage & Drives | ✅ |
| Hardware — Printers & Peripherals | ✅ |
| Mobile Devices (iOS & Android) | ✅ |
| Networking — IP Configuration (IPv4/IPv6) | ✅ |
| Networking — DNS, DHCP, VLANs | ✅ |
| Networking — Diagnostics & Troubleshooting | ✅ |
| Operating Systems — Windows Administration | ✅ |
| Operating Systems — Command Line & PowerShell | ✅ |
| Security — EFS File Sharing | ✅ |

---

## Skills

### IT Support & Administration
| Skill | Experience |
|---|---|
| Active Directory (Users, Groups, OUs, GPO) | Homelab — DC-01 Windows Server 2022 |
| PowerShell Scripting | 9 scripts across AD provisioning and troubleshooting |
| DNS / DHCP Troubleshooting | Diagnosed NIC misconfiguration causing name resolution failure |
| SMB File Shares & NTFS Permissions | Provisioned 4 department shares with group-based access control |
| osTicket Helpdesk Platform | Deployed and integrated with AD authentication |
| Windows 10 / Windows Server 2022 | Daily lab environment |
| Ubuntu Server (20.04, 22.04, 24.04) | Wazuh, osTicket, infrastructure VMs |
| Python | Google IT Automation with Python — Coursera |

### Security & Monitoring
| Skill | Experience |
|---|---|
| Wazuh SIEM/XDR | Deployed, configured agents, wrote suppression rules |
| Sysmon (SwiftOnSecurity config) | Deployed on DC-01 and WS-01 for endpoint telemetry |
| Log Analysis | Windows Security Events (EID 4625, 4740, 4648) |
| Attack Simulation | SMB brute force via CrackMapExec, Nmap reconnaissance |
| MITRE ATT&CK Framework | T1110 (Brute Force), T1105 (Ingress Tool Transfer), T1059.001 |
| Alert Tuning | Investigated false positive, wrote targeted suppression rule |

### Networking
| Skill | Experience |
|---|---|
| TCP/IP (IPv4 / IPv6) | Configured static IPs across all lab VMs |
| DNS | Troubleshot DNS resolution failure, configured DNS server roles |
| DHCP | Lab coursework + server configuration |
| VLANs | uCertify labs + pfSense segmentation planned |
| Network Diagnostics | ping, tracert, nslookup, ipconfig, netstat, net view, port testing |
| Proxmox Virtualization | Full homelab provisioning and VM management |

---

## Quick Glance

| | |
|---|---|
| 🔭 Currently working on | ARGUS — expanding Phase 1 attack simulations and building toward the full SOAR pipeline |
| 🌱 Currently learning | CompTIA Security+ (50%) · Detection Engineering · SOAR (TheHive, Cortex, Shuffle) · pfSense network segmentation |
| 👯 Looking to collaborate on | Homelab projects, SOC automation, CTF writeups, or anything blue team |
| 💬 Ask me about | Building a homelab from scratch · Wazuh SIEM · AD automation with PowerShell · Breaking into IT from a non-tech background |
| 📫 How to reach me | [Ademoladurodola16@gmail.com](mailto:Ademoladurodola16@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ademola-durodola-b2070432a/) |
| 😄 Pronouns | He / Him |
| ⚡ Fun fact | I was born with white hair — growing up in Nigeria, they called me the wisdom child |

---

## Work Ethic & Beliefs

I approach every role and every lab the same way: build it, break it, rebuild it until I understand it. When I encounter something I do not know, that is the beginning of the work — not a reason to stop.

---

*This portfolio is a living document — updated as the lab grows.*
