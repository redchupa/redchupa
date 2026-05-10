# Joseph Woo · `redchupa`

> Principal security researcher · Penetration tester · I read code looking for what shouldn't be there

🇰🇷 South Korea · 🔍 Find vulnerabilities · 🛡️ Drive remediation · 🛠️ Build on the side

---

## What I work on

Principal researcher at a cybersecurity firm — penetration testing, vulnerability research, and source-code audits across the modern stack. I find the bugs automated scanners miss and drive the remediation before anyone else stumbles into them. I read code looking for what shouldn't be there: deserialization chains, broken auth, race conditions, side-channels in places people stopped looking.

I lean generalist over specialist — the most interesting bugs tend to live where one domain ends and another begins. I've spent time teaching coding, too, which keeps me honest about explaining findings to people who aren't security folks.

On the side I build Home Assistant integrations for things that don't have public APIs — utility bills, real-time disaster alerts, transit, school meals — sourced from Korean government and public-data portals. Most of the side stuff is Python with authenticated session handling, on top of a self-hosted HA / SmartThings / Node-RED stack. When the wire format gets weird, I reverse-engineer it.

---

## 🏆 Selected achievements

- **2025** — **Korea Exchange (KRX) Chairman's Commendation for Information Security Merit** &nbsp;·&nbsp; 정보보호 유공 한국거래소 이사장 표창
- **2014** — **1st place, 9th Winter Hacking Camp CTF** (team `dog`) &nbsp;·&nbsp; 제9회 동계해킹캠프 CTF해킹대회 우승

---

## 🎯 Coverage

**Primary**
- Web app security — auth bypass, IDOR, deserialization chains, request smuggling, SSRF
- Source-code audits — the bugs that didn't make the changelog
- Reverse engineering — static analysis, patch diffing, fuzzing harness design

**Adjacent (working knowledge)**
- Mobile (iOS / Android) — runtime instrumentation, cert-pinning bypass, secure-storage flaws
- Cloud — IAM misconfig, container escapes, metadata abuse
- IoT / embedded — firmware extraction, protocol analysis
- Kernel & low-level — privilege escalation primitives, syscall surface
- Hardware — JTAG / UART entry points, side-channel basics
- AI / LLM red-team — prompt injection, context exfiltration, agent abuse

I lean generalist over specialist; the most interesting bugs tend to live where one domain ends and another begins.

---

## ⚙️ Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Lua](https://img.shields.io/badge/-Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Home Assistant](https://img.shields.io/badge/-Home_Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)
![SmartThings](https://img.shields.io/badge/-SmartThings-15BFFF?style=for-the-badge&logo=smartthings&logoColor=white)
![Node-RED](https://img.shields.io/badge/-Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white)
![MQTT](https://img.shields.io/badge/-MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

---

## 🛠️ Featured Projects

### 🇰🇷 [`kr_component_kit`](https://github.com/redchupa/kr_component_kit) &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; HACS
Home Assistant integration bundling **13 Korea-only public services** as native entities — `kepco`, `arisu`, `gasapp`, `safety_alert`, `disaster`, `kma_weather`, `airkorea`, `earthquake`, `pharmacy`, `fuel`, `school`, `transit`, `weather`. Each ships with an LLM tool for natural-Korean voice queries. Authenticated scraping where APIs don't exist, idempotent config flow, multi-region support.

### 🎟️ [`ha-app-dhlottery`](https://github.com/redchupa/ha-app-dhlottery) &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; `Docker`
Korean DH Lottery 6/45 auto-buy & analysis Home Assistant Add-on. MQTT Discovery, REST API with Swagger UI, hot/cold statistical analysis, encrypted credential storage.

### 📺 [`youtube_monitoring_addon`](https://github.com/redchupa/youtube_monitoring_addon) &nbsp;·&nbsp; `Python`
Cookie-based YouTube watch-history tracker as a Home Assistant add-on.

### 🚀 [`smartthings-edge-driver`](https://github.com/redchupa/smartthings-edge-driver) &nbsp;·&nbsp; `Lua`
SmartThings Edge driver collection running on the SmartThings hub.

---

## 🤝 Connect

<a href="https://github.com/sponsors/redchupa"><img src="https://img.shields.io/badge/Sponsor-❤️-pink?style=for-the-badge" /></a>
<a href="https://github.com/redchupa?tab=repositories"><img src="https://img.shields.io/badge/All_repos-→-blue?style=for-the-badge&logo=github" /></a>
