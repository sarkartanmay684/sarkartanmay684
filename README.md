# Tanmay Surjyakanta Sarkar

**Identity & Access Management · Security Operations · Digital Forensics & Incident Response · GRC**

CompTIA CySA+ · CompTIA Security+ · M.S. Cybersecurity, UMBC

I spent four years at Tata Consultancy Services building the role-based access logic that decided which users could reach which financial functions for a banking client. Since then I have moved to the other side of that problem: verifying access controls rather than writing them. My graduate research, under National Security Agency technical mentorship, applied formal methods to a cryptographic protocol.

Baltimore, MD  
[Resume (PDF)](https://github.com/sarkartanmay684/sarkartanmay684/blob/main/Tanmay_Sarkar_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/tanmay-surjyakanta-sarkar-5236302a7/) · tsarkar1@umbc.edu

---

## Projects

### [Cloud-Based Active Directory Setup and User Management](https://github.com/sarkartanmay684/Cloud-Based-Active-Directory-Setup-and-User-Management)
An Active Directory lab on Azure virtual machines that took **57,500 failed RDP authentication attempts over 44 hours** — roughly 1,300 an hour — through a permissive default network security group rule exposing TCP/3389. Detected it, traced the cause, remediated, and verified the drop in Security log volume. Windows event correlation across 4624/4625, 4720/4725/4726 and 4732/4733.

`Azure` · `Active Directory` · `PowerShell` · `Windows Event Analysis` · `Incident Response`

### [Cloud Security Risk Assessment — Azure GRC Simulation](https://github.com/sarkartanmay684/Cloud-Security-Risk-Assessment-GRC-Simulation-Azure)
A nine-item scored risk register (2 Critical, 2 High, 4 Medium, 1 Low) mapped to NIST CSF 1.1 and CIS Controls v8, with asset inventory, control mapping and a tiered remediation roadmap. Non-exploitative audit methodology, with scope limitations documented rather than hidden.

`NIST CSF` · `CIS Controls v8` · `Risk Assessment` · `Azure` · `Compliance`

### [Linux Log Analysis, Automation and SIEM Visualization](https://github.com/sarkartanmay684/Linux-Log-File-Analysis-Automation-and-SIEM-Visualization)
Investigated a distributed SSH brute-force campaign across 47 source hosts. The useful finding was a failure: a "Failed password" rule matched **zero of 490 real authentication failures**, because the host logged through the PAM stack rather than in OpenSSH format. A detection rule firing on nothing is indistinguishable from a quiet environment.

`Splunk` · `SPL` · `Python` · `Detection Engineering` · `Log Analysis`

### [Network Scanning and Host Enumeration using Nmap](https://github.com/sarkartanmay684/Network-Scanning-and-Host-Enumeration-using-Nmap)
Authorized reconnaissance across a /24 subnet with flag-by-flag methodology documentation. Manually validated an automated Slowloris (CVE-2007-6750) finding and downgraded it as a false positive, then remediated two exposed local services.

`Nmap` · `Network Security` · `Vulnerability Triage`

---

## Research

**Formal-methods analysis of the SecureDNA protocol** — INSuRE research program, UMBC · Fall 2024  
Technical mentor: National Security Agency · Faculty: Dr. Alan T. Sherman

One of five researchers analysing SecureDNA, a system that screens DNA synthesis requests against hazardous-sequence databases without exposing their contents. Modelled its registration, authentication and exemption-token workflows in the Cryptographic Protocol Shapes Analyzer (CPSA); assessed certificate chains of trust, Exemption List Tokens and hardware multi-factor authentication; and built an adversarial model covering key-server compromise, cryptographic assumptions and post-quantum exposure. The report is not publicly released.

`Formal Methods` · `CPSA` · `Cryptographic Protocols` · `Threat Modelling`

---

## Currently building

- **hybrid-identity-lab** — on-premises Active Directory synchronised to Microsoft Entra ID with Entra Connect
- **identity-lifecycle-automation** — joiner-mover-leaver automation against the Microsoft Graph API
- **detection-as-code** — portable Sigma detection rules mapped to MITRE ATT&CK, tested in CI
- **incident-response-rdp-bruteforce** — a full incident response investigation of the RDP campaign above

---

## Background

**Graduate coursework (M.S. Cybersecurity, UMBC)** — Enterprise Security, Cyber Operations Management, Risk Analysis & Compliance, Cyber Law & Policy, and 22 hands-on labs across two disciplines. Digital forensics and incident response: memory forensics with Volatility, disk imaging with FTK Imager and ProDiscover, registry and browser artifacts, static malware analysis, packet capture and NetFlow analysis, NIDS/NIPS and proxy analysis, IOC development with OpenIOC. Offensive security testing in controlled lab environments: OSINT, network mapping, vulnerability analysis with Nessus, exploitation with Metasploit, web testing with Burp Suite, and wireless and social engineering assessment.

**Four years production engineering** — Java, Spring, Hibernate, SQL stored procedures and schedulers, IBM WebSphere on Linux, delivered under a regulated SDLC with formal change control for a banking client. Four company awards.

**Certifications and training** — CompTIA CySA+ · CompTIA Security+ · TryHackMe SOC Level 1 · TryHackMe Cybersecurity 101

**Publication** — *Advanced Traffic Control Safety and Security in Vehicle using IoT*, National Conference on Emerging Trends in Applied Sciences of Engineering, Mumbai University, May 2019 (paper ID NCRTSE1906066).
