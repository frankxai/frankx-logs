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
