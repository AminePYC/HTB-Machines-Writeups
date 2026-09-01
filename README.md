<div align="center">

# HTB Machine Writeups
### HackTheBox — Retired Machine Solutions

![HackTheBox](https://img.shields.io/badge/Platform-HackTheBox-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![Machines](https://img.shields.io/badge/Machines_Rooted-0-9FEF00?style=flat-square)

</div>

---

> ⚠️ **Policy Notice**
> All writeups in this repository are for **retired 
> machines only**, published in compliance with 
> HackTheBox's writeup policy. No active machine 
> solutions are documented here.

---

## Index

| # | Machine | OS | Difficulty | Category | Writeup |
|---|---|---|---|---|---|
| — | *Coming soon* | — | — | — | — |

*Table updates as machines are completed and retired.*

---

## Approach

Every writeup follows the same structure:

```
Reconnaissance → Foothold → Privilege Escalation → Detection Opportunities
```

The **Detection Opportunities** section is the most 
important part of each writeup — it answers:
*"How would a SOC analyst catch this attack in a 
real environment?"*

This perspective comes from building toward a 
**blue team career**, not just solving challenges 
for the sake of it.

---

## Skills Demonstrated

**Reconnaissance**
- Port scanning and service enumeration (Nmap)
- Web content discovery (Gobuster, Feroxbuster)
- Service fingerprinting

**Exploitation**
- Web application vulnerabilities
- Service exploitation
- Credential attacks

**Privilege Escalation**
- Linux — SUID, cron jobs, capabilities, sudo
- Windows — token impersonation, service misconfigs
- Active Directory — Kerberoasting, AS-REP roasting

**Post-Exploitation**
- Lateral movement
- Credential harvesting
- Persistence mechanisms

**Detection (Blue Team Perspective)**
- MITRE ATT&CK technique mapping per machine
- Log sources that would expose each attack stage
- Detection rule logic for key techniques

---

## Tools Used

| Category | Tools |
|---|---|
| Recon | Nmap · Gobuster · Feroxbuster · Whatweb |
| Exploitation | Metasploit · Manual exploits · Burp Suite |
| Windows | Mimikatz · BloodHound · PowerView |
| Linux | LinPEAS · pspy · GTFObins |
| AD | BloodHound · Impacket · Rubeus · CrackMapExec |
| Password | Hashcat · John · Hydra |
| General | CyberChef · curl · Python |

---

## MITRE ATT&CK Coverage

Techniques encountered across machines are tracked and linked to the relevant writeup.

| Technique | ID | Machine |
|---|---|---|
| *Populates as machines are completed* | — | — |

---

## Stats

![Machines](https://img.shields.io/badge/Total_Machines-0-9FEF00?style=flat-square)
![Easy](https://img.shields.io/badge/Easy-0-green?style=flat-square)
![Medium](https://img.shields.io/badge/Medium-0-yellow?style=flat-square)
![Hard](https://img.shields.io/badge/Hard-0-red?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-0-orange?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-0-blue?style=flat-square)

---

## Structure

```
htb-machines-writeups/
├── README.md
├── easy/
│   ├── linux/
│   │   └── [machine-name]/
│   │       ├── writeup.md
│   │       └── screenshots/
│   └── windows/
│       └── [machine-name]/
│           ├── writeup.md
│           └── screenshots/
├── medium/
│   ├── linux/
│   └── windows/
└── hard/
    ├── linux/
    └── windows/
```

---

<div align="center">

*Every machine teaches something about how attackers 
think — and how defenders can catch them.*

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://[your-portfolio-url])
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/[your-handle])

</div>
