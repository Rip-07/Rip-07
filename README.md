### Askhat Akhtanov

Backend and integration engineer from Almaty, Kazakhstan. I connect systems that were never meant to talk to each other — APIs, CRMs, internal tools — and make them reliable enough to forget about. Lately: giving AI agents safe, scoped access to business systems through MCP.

[fahrentech.kz](https://fahrentech.kz) · [info@fahrentech.kz](mailto:info@fahrentech.kz) · [☕ Ko-fi](https://ko-fi.com/fahrentech) · Русский / Қазақша / English

---

#### Projects

| | |
|---|---|
| **[FahrenHack](https://github.com/Rip-07/FahrenHack)** | Open-source trainer for single-player PC games: console-style UI with gamepad support, ready-made game profiles with pointer-chain calibration, a Cheat Engine–style memory scanner and a phone remote over LAN. Rust · Windows |
| **[unraid-telegram-bot](https://github.com/Rip-07/unraid-telegram-bot)** | Telegram bot to start, stop, restart and read logs of Docker containers on Unraid, with per-user, per-container permissions in PostgreSQL, a denylist and an allowlist-only `/exec`. Java 21 · Spring Boot |
| **[wake-on-lan](https://github.com/Rip-07/wake-on-lan)** | Wake-on-LAN microservice: computers are stored in PostgreSQL, an API-key protected HTTP endpoint sends the magic packet. Wake from the iPhone Action Button via Shortcuts. Rust · Axum · SeaORM |
| **[bitrix24-mcp](https://github.com/Rip-07/bitrix24-mcp)** | MCP server that lets Claude, Cursor and other AI agents work with Bitrix24 CRM: deals, contacts, leads, tasks. Read-only by default, webhook secrets never reach logs. Python · MCP SDK 2 |
| **[pc-monitor-bot](https://github.com/Rip-07/pc-monitor-bot)** | Telegram bot that notifies you when your computers go online or offline, with `/status` on demand and a single authorized user. Python · python-telegram-bot |
| **[rdp-proxy](https://github.com/Rip-07/rdp-proxy)** | Small transparent TCP proxy that exposes an RDP host reachable over WireGuard, with IP allow-lists, connection limits, a health endpoint and Prometheus metrics. Rust · Tokio |

#### How I work

- Least privilege by default — for services and for AI agents: read-only modes, scoped tokens, non-root containers.
- Secrets stay out of logs and error messages.
- Failures are expected: timeouts, retries with backoff, health checks, metrics.
- Everything self-hostable: Docker, PostgreSQL, CI that runs lint and tests on every push.

#### Stack

**Daily:** Python (FastAPI, asyncio, pydantic) · PostgreSQL · Redis · Docker · TypeScript/React<br>
**Also:** Rust (Tokio, Axum) · C#/.NET · Java · MCP · Gitea Actions · Linux / Unraid

---

All projects are free and MIT-licensed. If they save you time, you can support my work on [Ko-fi](https://ko-fi.com/fahrentech) ☕
