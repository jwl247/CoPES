# CoPES — Coordinated Process Engine Substrate
### Phoenix DevOps OS | jwl247 | GPL v3

One command. Everything running.

```bash
git clone https://github.com/jwl247/CoPES.git
cd CoPES
bash install/bootstrap.sh
```

## What This Is
CoPES is the substrate. It powers Phoenix DevOps OS and the Life First App — a self-hosted AI companion built for people who need it and can't afford $700/month subscriptions.

Same engine. Everything runs on it.

## Components
- **Helix** — clone pool engine, QuadEngine, egress translation. 770k ops/sec.
- **Package Handler** — intake authority. Every file goes through here.
- **Frank** — output coordinator, Ring 3 comms.
- **Distro Handler** — 7 distros pre-registered, local first, silent updates.
- **intake.sh** — universal file intake pipeline v1.7.0.

## Requirements
- Ubuntu Server 24.04 LTS
- Python 3.10+
- Git

## Status
Active development. GPL v3. Anthropic credited — Claude ships with Phoenix.

## Co-founders
Jerry Leftwich (architecture, systems) + Jerilynn Leftwich (UX, InfoSec, red team)
