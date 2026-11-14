<div align="center">

# Muhammad Jameel

**Cybersecurity · VAPT · Web Application Security · Defensive Tooling**

[![Portfolio](https://img.shields.io/badge/Portfolio-jameel066.github.io-0ea5e9?style=flat-square&logo=googlechrome&logoColor=white)](https://jameel066.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-jameel066-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jameel066)
[![Focus](https://img.shields.io/badge/focus-VAPT%20%26%20appsec-2ea44f?style=flat-square)](#-focus-areas)

</div>

---

I break things on purpose so they can be fixed properly. My interest sits on both
sides of the line: **testing systems the way an attacker would**, then **building
tooling that removes the weakness instead of just reporting it**.

Right now I am going deep on VAPT methodology, web application security, and
Python/PowerShell tooling. Everything published here is code I actually run — no
copy-paste projects, no inflated claims.

## 🎯 Focus areas

| Area | What that means in practice |
| --- | --- |
| **Web application security** | OWASP Top 10 testing: authentication and session flaws, injection, broken access control, security misconfiguration |
| **VAPT** | Recon and enumeration, vulnerability validation, proof-of-concept evidence, remediation-focused reporting |
| **Defensive engineering** | Hardening Windows endpoints, designing authentication that survives a config leak, keeping audit trails |
| **Automation** | Python and PowerShell tooling that replaces manual, error-prone steps |

## 🚀 Featured projects

| Project | What it does | Built with |
| --- | --- | --- |
| 🛡️ **[SENTINEL](https://github.com/jameel066/sentinel)** | Access-protection layer for Windows workstations. Progressive lockout (15 s → 30 min), webcam intruder capture, SMTP alerts — fully local, no cloud. Security designed in: PBKDF2-HMAC-SHA256 (310k iterations, per-user salt), DPAPI-encrypted credentials, constant-time comparison, zero runtime package installs. 13 unit tests + CI. | `Python` `Tkinter` `DPAPI` `PBKDF2` |
| 📍 **[Live Location Tracker](https://github.com/jameel066/live-location)** | Flask + React web app for real-time location sharing with a family-safety angle. Token-based email verification, REST auth API, health endpoint for deployment monitoring. | `Python` `Flask` `React` `SQLite` |
| ⚙️ **[ESP32 Device Monitor](https://github.com/jameel066/esp32-device-monitor)** | Firmware for a networked ESP32 device: captive-portal Wi-Fi provisioning, EEPROM-backed config, Firebase sync, NTP time, and an offline mode that buffers when the network drops. | `C++` `ESP32` `Arduino` |

## 🧰 Toolbox

```text
Languages    Python · PowerShell · C++ · SQL · JavaScript
Web          Flask · React · REST APIs
Security     Burp Suite · Nmap · Wireshark · OWASP Top 10 · threat modelling
Platforms    Windows (DPAPI, registry, Tkinter) · Linux · ESP32/Arduino
Workflow     Git · GitHub Actions · virtualenv/pip
```

## 📊 GitHub

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=jameel066&show_icons=true&hide_border=true&hide_title=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jameel066&layout=compact&hide_border=true&langs_count=6" alt="Top languages" />

</div>

## 🤝 Connect

- 🌐 Portfolio — **[jameel066.github.io](https://jameel066.github.io)**
- 💬 Open to conversations about web app security, VAPT and defensive tooling
- 🐛 Found an issue in one of my projects? Open an issue — or a private advisory
  on the repository if it is security-relevant.

<div align="center">
<sub>Build it, break it, fix it, document it — then ship the tool so nobody has to do it twice.</sub>
</div>
