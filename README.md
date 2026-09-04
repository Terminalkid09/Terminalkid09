# Terminalkid09 — Backend & Security Engineer

16-year-old self-taught developer from Italy. I build production-grade security systems: MITM interception tools, C2 frameworks, SIEM platforms, honeypot networks, and AI-powered security tooling.

**Live Portfolio:** https://terminalkid09-portfolio-react.netlify.app/

---

## Main Projects

### 🕷️ Nyx — Professional MITM & Traffic Analysis Desktop App v1.0.0
Electron + React + FastAPI + mitmproxy desktop application for professional MITM interception and traffic analysis. Features: transparent proxy with DHCP-first stealth + ARP fallback, QUIC/HTTP3 blocking (forces TCP/TLS fallback), Activity Monitor (live SNI + HTTP Host per target without CA), HAR 1.2 export, 340+ vulnerability scanner, fuzzer, collaborator OOB server, session handling, match/replace, guaranteed clean shutdown (3-layer: API graceful + signal handlers + atexit). Competitive with Burp Suite for LAN interception — zero-config device onboarding, no CA required for metadata visibility. 606 backend tests, 0 ESLint errors, silent installer.

**GitHub:** https://github.com/Terminalkid09/nyx

### 👻 Phantom — Autonomous Red Team Framework v2.0.0
Full-spectrum offensive security framework with three integrated modes: (1) C2 Operations Center — cross-platform beacons (Windows PE, Linux ELF, Android ARM64, macOS) with AES-256-GCM + mTLS + HMAC, 35+ commands (shell, screenshot, keylog, inject, SOCKS5, SMB pipe, browser/CDP pivot, cookies, GPS, camera, audio), reflective in-memory loading, NTDLL unhooking, sleep masking, Ekko obfuscation, indirect/direct syscalls; (2) 12 Interactive Pentest Modules — scan, OSINT, web, exploit, brute, payload, handler, analyzer, pivot, wifi, wordlist, report with state-aware suggestions; (3) Autonomous Kill-Chain Agent (WIP) — deterministic planner + anomaly engine for autonomous kill chain execution (recon → exploit → beacon deploy → persistence → lateral), sub-agents for parallel campaigns, social engineering chain (persona → breach check → phish delivery → IP grab → network pivot). Includes React + TypeScript Electron GUI (18 views), 101 tests, Docker CI/CD. 68k LOC across Python/C++/ASM/TS.

**GitHub:** https://github.com/Terminalkid09/phantom

### 🛡️ Aegis — XDR/SIEM Ecosystem v3.0.0
Production-grade XDR/SIEM platform with 5 microservices: Java/Spring Boot ingestion gateway (syslog UDP + HTTP), Python/FastAPI correlation engine (200+ threat signatures), cross-platform Java/JNA endpoint agent, host telemetry agent, and React dashboard with 12 views. SOAR playbook engine, AI analysis (Ollama), anomaly detection, VaultX encrypted notes, full monitoring stack.

**GitHub:** https://github.com/Terminalkid09/aegis-ecosystem

### 🐙 Kraken — Honeypot Intelligence Platform v1.0.0
Multi-protocol honeypot network (SSH, HTTP, FTP, Telnet) with real-time attack detection, GeoIP enrichment, interactive Docker sandboxes, JWT auth, Telegram alerts, full Prometheus/Grafana/Alertmanager monitoring stack. Export intelligence reports in CSV, JSON, PDF. Containerized with 10 services.

**GitHub:** https://github.com/Terminalkid09/kraken

---

## Other Projects

- **🖲️ NodeTrace** — Multi-agent monitoring platform (Python, C#, C++, Java agents)
- **🤖 OSINT Discord Bot** — Modular async Discord bot for OSINT recon
- **🔐 VaultX** — Secure full-stack note management (React + Node.js + MongoDB)
- **🛡️ AI Security Suite** — ML-powered security toolkit (3 microservices)
- **📊 SQL Security Dashboard** — Security log analysis with 8 visualizations
- More on GitHub: https://github.com/Terminalkid09

---

## Skills

| Area | Technologies |
|------|-------------|
| **Languages** | Python, Java, C++, C#, JavaScript, TypeScript, SQL |
| **Backend** | FastAPI, Spring Boot, Node.js/Express, SQLAlchemy, Alembic, asyncio, aiohttp, mitmproxy |
| **Security** | C2 Frameworks, Beacon Dev (C++/ASM), AMSI/ETW Evasion, SIEM/XDR, Honeypots, OSINT, Penetration Testing, MITM/Proxy, WinDivert, Reflective Loading, Syscalls, Cryptography (AES-GCM, JWT, bcrypt, Argon2id) |
| **Infrastructure** | PostgreSQL, Redis, MongoDB, Docker, Docker Compose, Nginx, GitLab CI, GitHub Actions, Caddy |
| **Frontend & Desktop** | React, Vite, Tailwind CSS, Electron, TypeScript |
| **AI/ML** | Ollama, scikit-learn, TensorFlow/Keras, LLM Integration |
| **Tools** | mitmproxy, Ruff, mypy, pytest, Alembic |

---

## About Me

I learn by building real tools that solve real problems. My focus is on clean architecture, security fundamentals, and systems that work in production. Every project is containerized, tested, and CI/CD-ready.

**Contact:** [Terminalkid09@gmail.com](mailto:Terminalkid09@gmail.com) · [GitHub](https://github.com/Terminalkid09)