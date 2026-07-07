# ODAO — Karma Over Capital

**OASIS Decentralized Autonomous Organization**

ODAO is the governance layer of the OASIS Omniverse — a karma-based DAO where influence is earned through real-world positive impact, not bought with money. It reimagines what decentralized governance can be: a meritocracy of compassion rather than capital.

## Core Concept

In ODAO, voting power is proportional to your **karma score** — earned by rescuing animals, healing people, teaching classes, building things, and contributing positively to the ecosystem. You cannot buy your way in.

## What ODAO Governs

- Direction and priorities of the OASIS Omniverse roadmap
- Treasury allocation for grants, bounties and community initiatives
- Admission and removal of partner organisations
- Rule changes to the karma system itself
- Cross-app decisions affecting GHN, Noah's Ark ARN, JLA, GraceBook and Our World

## Karma → Voting Power

| Karma Tier | Label | Voting Weight |
|---|---|---|
| 0 – 9,999 | Initiate | 1× |
| 10,000 – 49,999 | Guardian | 5× |
| 50,000 – 199,999 | Elder | 20× |
| 200,000 – 999,999 | Luminary | 80× |
| 1,000,000+ | Ascended | 300× |

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Hosting | Static — any CDN or static host |

## Running Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powered by OASIS Web4*
