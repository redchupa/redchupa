# `redchupa`

> Principal security researcher · Penetration tester

🇰🇷 South Korea · 🔍 Find vulnerabilities · 🛡️ Drive remediation · 🛠️ Build on the side

---

## What I work on

Principal researcher at a cybersecurity firm — penetration testing, vulnerability research, and source-code audits. Most of my work is reading code and chasing the parts that don't quite add up: deserialization chains, broken auth, race conditions, the side-channels people stop looking at.

My background runs across most of the security stack — never the deepest tier of any one area, but useful when a finding crosses domain boundaries. I've spent time teaching coding too, which helps me write up findings in ways non-security folks can act on.

On the side I build Home Assistant integrations for things that don't have public APIs — utility bills, real-time disaster alerts, transit, school meals — sourced from Korean government and public-data portals. Most of the side stuff is Python with authenticated session handling, on top of a self-hosted HA / SmartThings / Node-RED stack. When the wire format gets weird, I reverse-engineer it.

---

## Recognition

- 2025 · Korea Exchange (KRX) Chairman's Commendation for Information Security Merit
- 2014 · 9th Winter Hacking Camp CTF — 1st place, team `dog`

---

## Coverage

**Primary**
- Web app security — auth bypass, IDOR, deserialization chains, request smuggling, SSRF
- Source-code audits — the bugs that don't surface in commit messages
- Reverse engineering — static analysis, patch diffing, fuzzing harness design

**Working knowledge**
- Mobile (iOS / Android) — runtime instrumentation, cert-pinning bypass, secure-storage flaws
- Cloud — IAM misconfig, container escapes, metadata abuse
- IoT / embedded — firmware extraction, protocol analysis
- Kernel & low-level — privilege escalation primitives, syscall surface
- Hardware — JTAG / UART entry points, side-channel basics
- AI / LLM red-team — prompt injection, context exfiltration, agent abuse

---

## ⚙️ Stack

**Languages**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/-Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Security Toolkit**

![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/-Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![nmap](https://img.shields.io/badge/-nmap-4682B4?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/-Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Ghidra](https://img.shields.io/badge/-Ghidra-ED2B2B?style=for-the-badge&logo=ghidra&logoColor=white)
![IDA Pro](https://img.shields.io/badge/-IDA_Pro-B70000?style=for-the-badge)
![Frida](https://img.shields.io/badge/-Frida-E33843?style=for-the-badge&logo=frida&logoColor=white)
![Hashcat](https://img.shields.io/badge/-Hashcat-2D2D2D?style=for-the-badge)
![radare2](https://img.shields.io/badge/-radare2-4F008C?style=for-the-badge)
![Volatility](https://img.shields.io/badge/-Volatility-6B5B95?style=for-the-badge)

**Source-code Audit & Fuzzing**

![Sparrow](https://img.shields.io/badge/-Sparrow-1E3A8A?style=for-the-badge)
![Fortify](https://img.shields.io/badge/-Fortify-B71C1C?style=for-the-badge)
![AFL++](https://img.shields.io/badge/-AFL%2B%2B-FF8C00?style=for-the-badge)
![angr](https://img.shields.io/badge/-angr-5C2D91?style=for-the-badge)

**Smart Home & Automation**

![Home Assistant](https://img.shields.io/badge/-Home_Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)
![SmartThings](https://img.shields.io/badge/-SmartThings-15BFFF?style=for-the-badge&logo=smartthings&logoColor=white)
![Node-RED](https://img.shields.io/badge/-Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![MQTT](https://img.shields.io/badge/-MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

**Self-hosted Infra**

![Synology DSM](https://img.shields.io/badge/-Synology_DSM-11B886?style=for-the-badge&logo=synology&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![WordPress](https://img.shields.io/badge/-WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Postfix · Dovecot](https://img.shields.io/badge/-Postfix_·_Dovecot-EE0000?style=for-the-badge&logo=maildotru&logoColor=white)

---

## 🛠️ Featured Projects

### [`kr_component_kit`](https://github.com/redchupa/kr_component_kit) &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; HACS
Home Assistant integration bundling **13 Korea-only public services** as native entities — `kepco`, `arisu`, `gasapp`, `safety_alert`, `disaster`, `kma_weather`, `airkorea`, `earthquake`, `pharmacy`, `fuel`, `school`, `transit`, `weather`. Each ships with an LLM tool for natural-Korean voice queries. Authenticated scraping where APIs don't exist, idempotent config flow, multi-region support.

### [`ha-app-dhlottery`](https://github.com/redchupa/ha-app-dhlottery) &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; `Docker`
Korean DH Lottery 6/45 auto-buy & analysis Home Assistant Add-on. MQTT Discovery, REST API with Swagger UI, hot/cold statistical analysis, encrypted credential storage.

### [`youtube_monitoring_addon`](https://github.com/redchupa/youtube_monitoring_addon) &nbsp;·&nbsp; `Python`
Cookie-based YouTube watch-history tracker as a Home Assistant add-on.

### [`smartthings-edge-driver`](https://github.com/redchupa/smartthings-edge-driver) &nbsp;·&nbsp; `Lua`
SmartThings Edge driver collection running on the SmartThings hub.

---

## Connect

<a href="https://github.com/sponsors/redchupa"><img src="https://img.shields.io/badge/Sponsor-❤️-pink?style=for-the-badge" /></a>
<a href="https://github.com/redchupa?tab=repositories"><img src="https://img.shields.io/badge/All_repos-→-blue?style=for-the-badge&logo=github" /></a>
