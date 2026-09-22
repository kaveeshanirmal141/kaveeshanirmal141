# Kaveesha Nirmal | Cloud Security & AIOps

![Image Alt](https://github.com/kaveeshanirmal141/kaveeshanirmal141/blob/main/readme%20art.jpeg?raw=true)

Cybersecurity Practitioner building a career in Cloud Security, with AI Operations (AIOps) as the layer that ties detection, automation and response together.

---

## What I actually do (in plain terms)

Cloud Security means finding and fixing the ways cloud environments like AWS and Azure get broken into: exposed credentials, over-permissioned IAM roles, and small misconfigurations that turn into full account takeover.

AIOps (Artificial Intelligence for IT Operations) means using AI and automation to handle the flood of logs, alerts and events a cloud environment produces, so real threats get caught and acted on instead of buried under noise.

My work sits where these two meet: understanding how cloud systems fail from an offensive point of view, then building the automated tooling that catches it before it becomes a breach.

---

## Core Focus
- Cloud Security: AWS (primary) and Azure (secondary), IAM misconfiguration, and full attack chains (SSRF to IMDS to temporary credentials to privilege escalation)
- AIOps and AI-driven security automation: using LLMs and agents to cut down manual alert triage and repetitive security work
- Vulnerability research: hands-on, published CVE work, not just lab exercises
- Offensive security fundamentals (Active Directory, web app exploitation, network defense) as the base everything above is built on

---

## Published Vulnerability Research

**CVE-2026-84741** - The Events Calendar (WordPress plugin, 600,000+ active installs)
- Unauthenticated disclosure of non-public venue and organizer data through the plugin's REST API, caused by a shared embedding helper missing a read-status check
- CVSS 5.3 (Medium), credited as Original Researcher, fixed by the vendor in version 6.17.5
- Found and reported independently through WPScan

Currently hunting across other StellarWP plugins (Restrict Content Pro, Event Tickets, LearnDash, GiveWP, KadenceWP), with more findings in WPScan's review queue.

---

## Current Focus
- AWS security skill-building through AWS Skill Builder, moving into Azure next.
- Hybrid Azure and on-premises Active Directory lab, built for internals-level SOC practice, not just deployment
- pfSense firewall lab in VMware: firewall rulebases, NAT (SNAT/DNAT), and now VLAN segmentation
- Python practice aimed at building real security tooling, not just exercises
- Ongoing WordPress plugin vulnerability research

---

## Experience
- Built and attacked a full Active Directory homelab (AD DS, ADCS, DNS, multi-host environment), including ADCS certificate-based attacks (ESC paths)
- Hands-on web exploitation across SQLi, SSRF, IDOR, SSTI, XXE, and RCE chains
- Built three isolated Docker homelabs demonstrating SQL injection, JWT manipulation, and a chained SQLi + JWT attack, exploited manually with no automation tools allowed
- Deployed and hardened Nginx and WordPress targets in Docker, documenting recon, findings, the fix applied, and re-scan verification for each
- Executed cloud attack paths (SSRF to IMDS to temporary credentials to privilege escalation)
- Consistent hands-on training (TryHackMe & HackTheBox)

---

## Tools & Tech

**Cloud**
AWS (IAM, S3, EC2 attack surface), Azure, GCP

**Offensive**
Kali Linux, Metasploit, Burp Suite, Nmap, OWASP ZAP, Netcat

**Analysis**
Wireshark, Splunk, Wazuh, Sentinel (basics)

**Infrastructure & Networking**
Docker, Docker Compose, pfSense, VMware Workstation, Nginx, GitHub, Vercel, Terraform, Kurbernetes

**Systems**
Windows Server 2022, Windows 10/11, Kali & Ubuntu Linux

**Development**
Python, Bash, PowerShell, HTML/CSS

**AI & Automation**
LLM fundamentals, prompt engineering, AI agents for security workflows, API integrations for automated detection and response

---

## Certifications & Training
- WEB-RTA - Web Red Team Analyst
- AD-RTS - Active Directory Red Team Specialist
- MCRTA - Multi-Cloud Red Team Analyst
- Working toward SC-500 (Microsoft Security Operations Analyst, Azure)
- TryHackMe - Top-ranked learner (top percentile globally)

---

## Projects
- **Plexavo** - Open-core cloud security tool built to find misconfigurations in AWS infrastructure
- WordPress plugin vulnerability research (CVE-2026-84741 and ongoing hunts)
- Active Directory attack lab (enterprise simulation with ADCS)
- Docker-based SQLi, JWT, and chain-attack homelabs
- Nginx and WordPress web server hardening labs
- Custom CTF labs (THM-style scenarios)
- Security write-ups and attack chain breakdowns

---

## Goal
Become a cloud security practitioner who builds the AI-driven detection and automation systems that defend the environments I know how to break, while shipping SaaS security tooling that real teams actually use.
