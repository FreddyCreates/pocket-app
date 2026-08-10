# POCKET App Hub

<p align="center"><img src="docs/brand/pocket-mark.svg" width="100" alt="POCKET"/></p>

**ItsNotAI Labs / Medina Tech Labs** — public user hub for **documentation**, **doors** (Edge · Electron · Phone), and **research downloads**.

> **License:** [POCKET Researcher License](LICENSE) — **research & evaluation only**.  
> Not a commercial product license. No resale / multi-tenant production without a written deal.

---

## Ecosystem

| Product | GitHub | Role |
|---------|--------|------|
| **POCKET host** | [ItsNotAILABS/pocket](https://github.com/ItsNotAILABS/pocket) | Multi-agent host · desk · phone · API |
| **POCKET Agent** | [ItsNotAILABS/pocket-agent](https://github.com/ItsNotAILABS/pocket-agent) | CLI + one-line install slices |
| **Pocket Voice** | [ItsNotAILABS/pocket-voice-to-text](https://github.com/ItsNotAILABS/pocket-voice-to-text) | Sovereign voice stack |
| **This hub** | pocket-app | Docs + doors for users (not the full runtime) |

---

## What this hub is

| Surface | Purpose |
|---------|---------|
| **Docs** | Editions, security, multi-user seats, API map |
| **Downloads** | Windows desk packages after license accept |
| **Doors** | Edge web desk · Phone · Electron (sovereign shell) · Install slices |

Core runtime lives in **pocket**. Agent CLI + mail/SDK slices live in **pocket-agent**.

---

## Doors (when host is up)

| Door | Path / action |
|------|----------------|
| Desk | `/desk` |
| Phone | `/phone` |
| **Docs hub** | `/docs` |
| **Agent Mail** | `/mail` |
| **Install slices** | `/install` (agent · SDK · skills · knowledge · capsules · **mail** · plug) |
| Work Studio | `/work` |
| Live catalog | `GET /v1/catalog` |
| Downloads | `/download` (license gate) |
| Electron | Local `desktop-electron` package — sovereign Owner/User profiles |
| Edge app | Operator: Edge `--app=http://127.0.0.1:8787/desk` |

Example public base: `https://pocket.medinatechlabs.net`

---

## Two editions (do not mix)

| | **Founder / Operator** | **Market / seat** |
|--|------------------------|-------------------|
| Who | Operators on **their** machine | Customers / invite seats |
| Files | Full local host | **Their** sandbox only |
| Electron | `POCKET_CLIENT_ROLE=operator` | Source picker → team URL or local |
| Never | — | Founder's personal disk |

**Invite ≠ “use my laptop.”** Invite = create **your** seat with **your** password.

---

## New product uses (2026)

- **Agent Mail** — `agents.pocket.local` accounts + inboxes for every agent  
- **Genetic flow** — internal models as modules that evolve which run  
- **Website UI engines** — models drive websites via Python MCP  
- **One-line slices** including **mail**:  
  `curl -fsSL https://raw.githubusercontent.com/ItsNotAILABS/pocket-agent/main/install/mail.sh | sh`  
- **Sovereign Electron 2.2** — navigation locked to desk origin; no password storage  
- **Docs + how-tos** — host `/docs` and repo `docs/how-to/`

---

## Documentation map

| Doc | Topic |
|-----|--------|
| pocket `docs/INDEX.md` | Master platform map |
| pocket `docs/HOW_TO.md` | How-to index |
| pocket `docs/how-to/AGENT_MAIL.md` | Agent Mail |
| pocket `docs/SECURITY.md` | Auth + isolation |
| pocket `docs/MULTI_USER.md` | Seats / invites |
| pocket `REPOS.md` | How repos are organized |

---

## License

Researcher License — research & evaluation. See [LICENSE](LICENSE) / [LICENSE-RESEARCHER.md](LICENSE-RESEARCHER.md).
