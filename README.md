# FrankX Development Logs

Visual progress tracking and session logs for all FrankX projects.

## Overview

This repository serves as a centralized log for all AI-assisted development sessions across:

- **FrankX** - Main website and content platform
- **Arcanea** - Fantasy game project
- **oracle-work** - Professional Oracle work
- **vibe-os** - Vibe OS product
- **claude-mem** - Claude memory plugin
- And 20+ more repositories

## Structure

```
frankx-logs/
├── sessions/           # Individual session logs
│   └── 2026/
│       └── 01/        # Monthly archives
├── daily/             # Daily summaries
├── weekly/            # Weekly intelligence reports
├── CHANGELOG.md       # Human-readable changelog
└── data/              # JSON data for visualizations
    ├── commits.json   # Aggregated commit data
    └── stats.json     # Repository statistics
```

## Usage

Logs are automatically generated using the `/log` command in Claude Code:

```bash
/log            # Full session with AI summary
/log --quick    # Fast, no AI (< 1 second)
/log --daily    # 24-hour report
/log --weekly   # 7-day intelligence report
```

## Live Dashboard

View the visual changelog at: [frankx.ai/changelog](https://frankx.ai/changelog)

## Stats

![Commits](https://img.shields.io/badge/dynamic/json?url=https://frankx.ai/api/logs/stats&query=$.totalCommits&label=Total%20Commits&color=emerald)
![Repos](https://img.shields.io/badge/Repositories-28-blue)
![Active](https://img.shields.io/badge/Status-Active-green)

---

*Powered by AI Session Logging System*

<!-- STARLIGHT:OPERATING:BEGIN v2 sha=9f8fecc91edc source=794db1e51a55a128816f7aa266eb0ac1dbd452c3 -->

## Agent operating guidance

Repository agents use the shared Starlight operating contract in `AGENTS.md` alongside local instructions.
The contract asks agents to establish a useful outcome, select relevant skills, complete authorized work,
verify current sources, refine the actual artifact, and report evidence and remaining gates.
It covers human agency, privacy, rights, resource stewardship and bounded proactivity.
Repository identity, brand, canon, build commands and release gates remain local.

[Pinned contract](https://github.com/frankxai/Starlight-Intelligence-System/blob/794db1e51a55a128816f7aa266eb0ac1dbd452c3/docs/architecture/agents-md/band-a.md)
· [Projection and verification](https://github.com/frankxai/Starlight-Intelligence-System/blob/794db1e51a55a128816f7aa266eb0ac1dbd452c3/docs/architecture/AGENTS-MD-CONTRACT.md)

These files supply operating guidance. They do not activate an agent, grant tool permissions,
schedule recurring work, certify compliance or prove a live capability.

<!-- STARLIGHT:OPERATING:END -->
