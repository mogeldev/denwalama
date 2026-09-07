# 🦙 Denwa Lama

A retro-styled desktop client for a remote [Ollama](https://ollama.com) server — connect over SSH, manage models, and watch host resources without touching a terminal.

**This repository hosts the public website and release downloads only.** The application source code is closed-source and not published here.

- **Website:** [mogeldev.github.io/denwalama](https://mogeldev.github.io/denwalama/)
- **Downloads:** [Releases](https://github.com/mogeldev/denwalama/releases)
- **License:** Freeware, no redistribution — see [LICENSE.txt](https://mogeldev.github.io/denwalama/license.html) (bundled with the app)

## Features

- Connect over SSH — standard authentication, no server-side agent
- Manage models — list, pull, stop, delete, batch-select
- Watch the host — live CPU/memory/disk/GPU utilization
- Read logs — tail journalctl or a log file directly
- Restart the Ollama service with automatic sudo fallback
- Test prompts against any OpenAI-compatible endpoint
- Save multiple named SSH connections, each with an optional saved password
- Full German/English UI, switchable live

## Platforms

| Platform | Status |
|---|---|
| Windows (x64) | Installer + portable ZIP |
| Linux (x64) | AppImage — experimental, untested |

Not affiliated with Ollama.

---

Built with [Claude](https://claude.com) (Anthropic) by [mogeldev](https://mogeldev.github.io/).
