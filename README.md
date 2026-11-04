<div align="center">

# Arman Abrahamyan

**Offensive security student · Yerevan, Armenia**

Active Directory attack paths · web exploitation · privilege escalation

[![Blog](https://img.shields.io/badge/Writeups-armanabr.github.io-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://armanabr.github.io/)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-Pro_Hacker-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/users/1934320)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/armcyb)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/armabrahamyan)
[![Resume](https://img.shields.io/badge/Resume-PDF-555555?style=for-the-badge&logo=readthedocs&logoColor=white)](https://armanabr.github.io/static/Arman_Abrahamyan_Resume.pdf)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:armanabrahamyan8080@gmail.com)

<a href="https://app.hackthebox.com/users/1934320">
  <img src="https://www.hackthebox.com/badge/image/1934320" alt="HackTheBox profile">
</a>

</div>

---

I break things on purpose, then write down exactly how, so the next person doesn't have to guess.

16-year-old offensive security student. 14 months as an offensive security intern at Hexens, a year as a software engineering intern before that, and every attack chain written up in public at [armanabr.github.io](https://armanabr.github.io/). Looking for offensive security internships or part-time work.

| | |
|---|---|
| 🥈 **2nd of 209** | Students National Cyber Challenge 2026, prequalification - solo, 10/10 flags, 3 first bloods |
| 🇦🇲 **Team Armenia** | European Cybersecurity Challenge (ECSC) 2026, Bochum |
| 🟩 **Pro Hacker** | HackTheBox - 40+ machines, 130+ challenges, level 65+ (Master) |
| 📝 **30+ writeups** | HTB machines, Sherlock DFIR scenarios and CTF challenges |

---

## Tools I built

**[AD-Path-Finder](https://github.com/ArmanAbr/AD-Path-Finder)** · Python
A mini-BloodHound. Turns Active Directory rights (GenericAll, WriteDacl, ForceChangePassword, DCSync) into a weighted graph and runs Dijkstra from any user to Domain Admin, fewest abuse steps first. Flags Kerberoastable, AS-REP roastable and unconstrained delegation quick wins.

**[SSTI-Exploiter](https://github.com/ArmanAbr/SSTI-Exploiter)** · Python
Tells real template evaluation apart from reflection with randomized probes, fingerprints 11 template engines and builds engine-specific RCE payloads, with a time-based fallback for blind targets. Ships with a vulnerable Flask lab.

**[Sentinel](https://github.com/ArmanAbr/Sentinel)** · Python
Privilege escalation engine. An offline GTFOBins/HackTricks rule engine ranks ready-to-run vectors, with an optional LLM layer that re-prioritises and chains them. Read-only by default.

Also: [AD-Enum-Toolkit](https://github.com/ArmanAbr/AD-Enum-Toolkit) · [Pentest-Automation](https://github.com/ArmanAbr/Pentest-Automation) · [CTF-Cheatsheets](https://github.com/ArmanAbr/CTF-Cheatsheets)

---

## Latest writeups

<!-- BLOG-POST-LIST:START -->
- [Browse all writeups](https://armanabr.github.io/)
<!-- BLOG-POST-LIST:END -->

---

## Competitions

- **Students National Cyber Challenge 2026, prequalification - 2nd of 209**
  ISAA on Hack The Box, jeopardy, individual. 10 scenarios across Web, Reversing, Pwn, Forensics, AI/ML, Crypto and OSINT in one 13-hour session, human-only (no AI assistants or automation). Cleared all 10 for 6,575 points; the top three tied on points, so placement came down to time. [Writeups](https://armanabr.github.io/)
- **ECSC 2026** (European Cybersecurity Challenge) - Bochum, Germany, Oct 12-16. Represented Armenia with Team Armenia.
- **Up next:** Students National Cyber Challenge 2026 final - Nov 14, team event.

---

## Experience

**Offensive Security Intern - Hexens** · Jul 2024 - Aug 2025 · Yerevan
Web application testing by hand in Burp Suite (SQLi, XSS, LFI/RFI, CSRF, SSRF, IDOR) and the full PortSwigger Web Security Academy path; Active Directory enumeration and abuse with BloodHound, token impersonation and ACL abuse; Linux and Windows privilege escalation; Python, Bash and PowerShell tooling to automate enumeration.

**Software Engineering Intern - DST (Database and Statistics Technology)** · Jun 2022 - May 2023 · Remote
Internal business tools in VB.NET / .NET Framework, MySQL schemas and reporting queries, REST endpoint testing in Postman. Knowing how applications get built is half of knowing how they break.

---

## Toolkit

**Offensive** - Burp Suite · Nmap · BloodHound · Impacket · NetExec · Evil-WinRM · Metasploit · Hashcat · Volatility · Wireshark · ffuf

**Languages** - Python · Bash · PowerShell · SQL · VB.NET · C++

**Platforms** - Linux · Windows · Active Directory · Kali

---

## Currently

- Working toward HTB CPTS
- Building an Active Directory home lab
- Rooting HackTheBox Windows and Linux machines and writing them up
