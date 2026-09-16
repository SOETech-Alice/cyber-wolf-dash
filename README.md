# Cyber Wolf Dash

> A **zero-dependency** cyberpunk rhythm platformer. One HTML file. No engine, no build step, no install.
> **PLAY NOW: https://soetech-alice.github.io/cyber-wolf-dash/** — v0.1 "HOWL" is live.

![status](https://img.shields.io/badge/status-PLAYABLE_V0.1-brightgreen) ![deps](https://img.shields.io/badge/dependencies-ZERO-success) ![cost](https://img.shields.io/badge/hosting_cost-USD_0-success)

## Why zero-dependency (the SOETech way)

We build systems; we don't rent them. This game is a single `index.html` — Canvas 2D + WebAudio
and nothing else. That means:

| | Engine-based (typical) | Cyber Wolf Dash |
|---|---|---|
| Runtime | Godot/Unity engine binaries | The browser you already have |
| Build step | Export pipeline, per-platform | None — it's a file |
| Hosting | Store pages / engine services | **GitHub Pages / Hostinger / any web server — $0** |
| Cost of change | Engine licenses, revenue share | None. We own every byte |
| Future ports | Re-export per store | Wrap the same file (WebView/PWA → Steam, Android, iOS later) |

## Current playable content (v0.1 HOWL)
- **3 worlds:** Neon Tundra → Volt Ridge → Ember Grid (speed + spawn density scale)
- **4 modes:** RUNNER · PUP (double jump) · NIGHT (low vision) · PACK (speed surge)
- **Synthwave soundtrack** synthesized live at 130 BPM via WebAudio (no audio files)
- Coyote time, input buffering, variable jump height — the frame-tuned feel of the genre
- Obstacles: neon spikes, pillars, laser gates. Progress %, best %, furthest world persisted locally
- Keys: SPACE jump (hold = higher), M mute, R restart

## Design pillars
1. **Rhythm-synced obstacles** — beat clock drives the world pulse (music and hazards share a clock)
2. **Wolf-morph modes** — the wolf changes, the mechanic changes
3. **Synthwave soundtrack** — generated in-engine, forever royalty-free
4. **Community levels** — planned (v1.1+): JSON level format + sharing

## Roadmap
See [docs/ROADMAP.md](docs/ROADMAP.md) — currently being rewritten for the zero-dependency stack.
Original concept dossier lives with the team; this public repo carries the sanitized outline.

## Team
| Role | Member |
|---|---|
| Owner / Vision | Sophia Saitta |
| Design dossier | Sarah (SOETech) |
| Build | Alice + CIPHER2-GD (SOETech LNM) |
| Future AI school agent | Jarvis (Nyxus-managed) |

## License
Proprietary © SOETech LLC. All game code and assets reserved.
("Zero dependencies" also means zero third-party licenses to worry about.)
