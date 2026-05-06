# Christian Herrera
Backend Engineer | Security-Focused · Node.js • Express.js • Electron.js • System Design

I build backend systems and pick them apart.

[Portfolio](https://ChristianHerrera.dev)

---

## Featured Projects

### WebWeavr — Passive Reconnaissance Platform
Live: [webweavr.christianherrera.dev](https://webweavr.christianherrera.dev) | [Repo](https://github.com/Chrisherr1/WebWeavr)

Zero-footprint OSINT tool that maps a target's external attack surface without generating traffic on their infrastructure.

- SSE-based streaming across 11 passive sources (CT logs, passive DNS, web archives)
- Dockerized behind Nginx with CSP, HSTS, and edge-layer rate limiting
- Node.js/Express backend with modular per-source adapters

---

### Blitzkrieg — Web Fuzzing GUI `WIP`
[Repo](https://github.com/Chrisherr1/Blitzkrieg)

Electron app that wraps ffuf and feroxbuster into a unified visual pipeline for web content discovery.

- Spawns fuzzing binaries as child processes via Node.js IPC — no performance overhead from the GUI layer
- Handles configuration, output parsing, and scan chaining across both tools
- Eliminates terminal context-switching during active engagements

---

### Kiki's Weather Delivery — Desktop Weather App
[Repo](https://github.com/Chrisherr1/Kiki-s-Weather-Delivery)

Cross-platform menu bar app (macOS/Windows) that delivers context-aware weather alerts passively via system tray.

- Pirate Weather API with startup location resolution to minimize repeated API calls
- Modular architecture separating tray, polling, and notification concerns
- Built with Electron; state managed in-process with no persistent window

---

### Notepad — Self-Hosted Note-Taking App
Live: [notepad.christianherrera.dev](https://notepad.christianherrera.dev) | [Repo](https://github.com/Chrisherr1/NotePad-Security-Project)

Self-hosted note-taking backend with Google OAuth 2.0 and a layered service architecture.

- OAuth 2.0 via Passport.js — no credential storage, eliminates password handling risk
- Service layer decouples route handlers from data access for consistent authz enforcement
- Deployed on a personal VPS behind Nginx reverse proxy with TLS termination at the edge

---

### IoT Monitoring via The Things Network
[Repo](https://github.com/Alanj818/Woope)

MQTT ingestion layer for a LoRaWAN sensor network on TTN with real-time telemetry and a REST API.

- Subscribes to TTN MQTT broker; deduplicates on device EUI and frame counter
- Express.js REST endpoints consumed by a React Native mobile client
- Handles out-of-order uplinks and unreliable transmission inherent to LoRaWAN

## Technologies

<p align="center">
  <img src="https://img.shields.io/badge/-Java-05122A?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=node.js"/>
  <img src="https://img.shields.io/badge/-Express-05122A?style=flat&logo=express"/>
  <img src="https://img.shields.io/badge/-Electron-05122A?style=flat&logo=electron"/>
  <img src="https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql"/>
  <img src="https://img.shields.io/badge/-MySQL-05122A?style=flat&logo=mysql"/>
  <img src="https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker"/>
  <img src="https://img.shields.io/badge/-Nginx-05122A?style=flat&logo=nginx"/>
  <img src="https://img.shields.io/badge/-Git-05122A?style=flat&logo=git"/>
  <img src="https://img.shields.io/badge/-Burp Suite-05122A?style=flat&logo=portswigger&logoColor=white"/>
  <img src="https://img.shields.io/badge/-ffuf-05122A?style=flat&logo=gnu-bash&logoColor=white"/>
</p>

---

## Currently Reading

- *The Design of Web APIs* — Arnaud Lauret  
  `██░░░░░░░░` 20% · Designing consistent, maintainable, consumer-friendly APIs.

- *Grokking Web Security* — Malcolm McDonald  
  `█████░░░░░` 50% · Practical web security concepts, common vulnerabilities, and defenses.

---

## Connect

<p align="center">
  <a href="https://christianherrera.dev">
    <img src="https://img.shields.io/badge/Portfolio-4B5563?style=flat&logo=Google-Chrome&logoColor=white"/>
  </a>
  <a href="https://linkedin.com/in/christianherreradev">
    <img src="https://img.shields.io/badge/LinkedIn-4B5563?style=flat&logo=Linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Chrisherr1">
    <img src="https://img.shields.io/badge/GitHub-4B5563?style=flat&logo=GitHub&logoColor=white"/>
  </a>
  <a href="mailto:Christian.herrera.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-4B5563?style=flat&logo=Gmail&logoColor=white"/>
  </a>
</p>
