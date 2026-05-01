<div align="center">

# Efe

**Backend Engineer · Systems Architect · Hardware Technician**

[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com)
[![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)](https://www.proxmox.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.linux.org)
[![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com)
[![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)](https://www.st.com)

</div>

---

I write backend systems and firmware. When something does not exist, I build it from scratch. Currently finishing a BSc in Informatics at KTU while running a Proxmox home lab and shipping open-source tools people actually clone.

CTO at World Study Hub SL. Relocating to Spain in August 2026 for the ASIR program at UAX.

---

## Featured Projects

### [Taskmanager J2534 Bridge](https://github.com/gorevyoneticisi/taskmanager-j2534)

A complete SAE J2534-1 v04.04 PassThru DLL written from scratch in C#. Connects a custom STM32F407-based CAN adapter to any Windows OBD2 diagnostic application, no proprietary hardware required.

- Full ISO15765-2 transport layer in the DLL: segmentation, reassembly, flow control
- Multi-channel, configurable pad byte per channel (BMW ISTA compatible)
- Confirmed working with Toyota Techstream, VW ODIS, Ford IDS, BMW ISTA-D
- Includes a dark-theme WinForms OBD2 reader for live sensor data and DTC management

[![taskmanager-j2534](https://github-readme-stats-nine-weld-69.vercel.app/api/pin/?username=gorevyoneticisi&repo=taskmanager-j2534&theme=tokyonight&hide_border=true)](https://github.com/gorevyoneticisi/taskmanager-j2534)

### Maritime Intelligence Command Center (MMIS)

Autonomous maritime data extraction and analysis engine.

- Node.js + Puppeteer with custom WAF bypass and memory-cycle browser management
- Tracks thousands of active vessel records across Alphaliner and ShipSelector fleets
- TOTP 2FA and HMAC-signed control planes for secure remote operation
- Deployed on a Proxmox cluster with Cloudflare Zero Trust access

---

## Infrastructure

HP EliteDesk and Lenovo ThinkCentre M710q cluster running Proxmox, Docker, and Cloudflare Zero Trust. All services are containerized and accessible via zero-config tunnels. No port forwarding, no exposed IPs.

---

## Stack

| Domain | Tools |
|---|---|
| Backend | Java (Spring Boot), Node.js, PostgreSQL |
| Infrastructure | Proxmox, Docker, Cloudflare Zero Trust, Linux |
| Systems | Windows IoT LTSC optimization, bare-metal tuning |
| Embedded | STM32, ESP32, CAN bus, OBD2 interfaces, PCB repair |

---

## Stats

<div align="center">

![GitHub Stats](https://github-readme-stats-nine-weld-69.vercel.app/api?username=gorevyoneticisi&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats-nine-weld-69.vercel.app/api/top-langs/?username=gorevyoneticisi&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Support

If any of my work saved you time or money, you can support it here:

- Revolut: `@gorevyoneticisi`
- PayPal: `gorevyoneticisi`

For collaboration, custom builds, or integration questions, open an issue on the relevant repo or reach out via GitHub.
