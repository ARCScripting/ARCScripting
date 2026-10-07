# Hi, I'm Allen 👋

I'm a self-hosted AI and automation tinkerer. By day I work in enterprise solution engineering; nights and weekends I run a home lab where I keep AI agents, GPU inference, mail, and monitoring humming — and I write the automation that maintains itself.

## What I build and run

- **Self-hosted AI agent ops** — a custom deployment of the open-source *Hermes* agent. A DST-safe nightly pipeline rebases it onto upstream bleeding edge, re-applies my local customizations, merges best-of-both, and smoke-tests before restart — the build advances every night without ever losing local fixes. (Some of that went back upstream: I contributed rich structured "decision card" options to Hermes' clarify tool.)
- **LLM inference on NVIDIA DGX Spark (GB10)** — serving large open models with vLLM — tensor-parallel splitting and NCCL tuning — and routing agents across fast and slow inference lanes.
- **Persistent memory stack** — session recall, code-graph queries, and cron-backed hydration/consolidation so agents get measurably smarter over time.
- **Ops bots & crons** — Discord thread bumping, nightly feature briefs, usage and uptime monitors, and a self-maintaining update loop. If it can be scheduled, it's scheduled.
- **Home-lab infrastructure** — Proxmox cluster, containers/VMs, reverse proxies, and a self-hosted mail stack (Postfix/Dovecot, DKIM/DMARC, per-domain TLS) serving custom domains.
- **Home network & energy** — cabled networking with mesh Wi-Fi and IP cameras, plus a slow march toward net-excess solar in North Texas.

## Toolbox

Python · Linux · Proxmox · Docker · Git · vLLM / NCCL · Discord API · nginx · Postfix / Dovecot · networking

## Find me

- [GitHub](https://github.com/ARCScripting) — this profile
- [LinkedIn](https://www.linkedin.com/in/allen-craig-05b10657/)
- Projects and ramblings usually surface in a small tech Discord I run
