---

## What is SOC and Network Security
SOC means Security Operations Center. It is the team that watches alerts and investigates threats in real time. Network security means protecting communication and data when it travels across internet. Together they make sure systems are safe and available for users.

---


## Project Overview
This repo is my first stage analysis of SOC operations and network security basics. I wrote it like how an analyst would explain after doing the work.

---

## Stage 1 – SOC Overview

### SOC Roles
| **Role** | **Work Done** |
|-------------|----------------|
| L1 Analyst | Watches alerts and filters false positives |
| L2 Analyst | Investigates deeper and checks logs |
| L3 Analyst | Does threat hunting and forensic analysis |

### SOC Workflow
| **Step** | **What Happens** |
|---------|----------------|
| Alert | SIEM or IDS raises alert |
| Investigation | Analyst checks logs and packets |
| Escalation | If confirmed then passed to higher tier |
| Response | Incident response team contains and recovers |

---

## Stage 2 – CIA Triad

| **Principle** | **Meaning** | **Example** |
|----------------|----------------|----------------|
| Confidentiality | Keep data safe from others | HTTPS protects login |
| Integrity | Data should not be changed | Hash check for file download |
| Availability | System should be up | DDoS protection keeps site running |

---

## Stage 3 – Networking Basics

### IP Addressing
| **Type** | **Details** |
|---------|----------------|
| IPv4 | 32 bit and 5 classes A to E |
| IPv6 | 128 bit and huge address space |

### Private vs Public IP
- **Private IP** → Used inside LAN like 192.168.x.x  
- **Public IP** → Used on internet and globally routable  

### DNS, HTTP, HTTPS
| **Protocol** | **Purpose** |
|-------------|----------------|
| DNS | Resolves domain name to IP |
| HTTP | Transfers web data without encryption |
| HTTPS | Secure HTTP with TLS |

### Internet Communication
Packets go through routers and DNS resolves domain and TLS secures session.  
**How internet communication works** → Browser sends request → DNS resolves → Server replies.

---

## Stage 4 – Security Basics

| **Threat** | **Meaning** | **Example** |
|-------------|----------------|----------------|
| Malware | Malicious software | Trojan stealing data |
| Phishing | Fake email or site | Bank login page copy |
| Brute Force | Repeated password tries | SSH login attack |
| MITRE ATT&CK | Framework of attack techniques | Credential dumping and lateral movement |

---

## Final Comparison Table

| **Topic** | **Key Points** | **Analysis Done** |
|-----------|----------------|-------------------|
| SOC Roles | L1 L2 L3 | Checked responsibilities |
| SOC Workflow | Alert to Response | Followed investigation steps |
| CIA Triad | Confidentiality Integrity Availability | Linked with real examples |
| Networking | IPv4 IPv6 DNS HTTP HTTPS | Explained communication flow |
| Security Basics | Malware Phishing Brute Force MITRE | Studied attack methods |

---

## Conclusion
This stage analysis gave me clear idea of SOC workflow and CIA triad and networking basics and common threats. Next stage I will do packet capture and log analysis with real tools.

---

