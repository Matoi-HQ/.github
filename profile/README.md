<p align="center">
  <img src="https://raw.githubusercontent.com/matoi-dev/.github/main/profile/assets/matoi-banner.svg" alt="Matoi" width="100%" />
</p>

<p align="center">
  <strong>纏 — Where teams rally.</strong>
</p>

<p align="center">
  <a href="https://matoi.dev">Website</a> ·
  <a href="https://matoi.dev/docs">Docs</a> ·
  <a href="https://matoi.dev/changelog">Changelog</a> ·
  <a href="https://discord.gg/matoi">Discord</a> ·
  <a href="https://twitter.com/matoidev">Twitter</a>
</p>

<p align="center">
  <a href="https://matoi.dev"><img src="https://img.shields.io/badge/status-early%20access-c4432e?style=flat-square" alt="Status" /></a>
  <a href="https://github.com/matoi-dev"><img src="https://img.shields.io/github/stars/matoi-dev?style=flat-square&color=c49a3c&label=stars" alt="Stars" /></a>
  <a href="https://discord.gg/matoi"><img src="https://img.shields.io/badge/discord-join-3d4f7c?style=flat-square" alt="Discord" /></a>
  <a href="https://matoi.dev/license"><img src="https://img.shields.io/badge/license-MIT-4a6b5a?style=flat-square" alt="License" /></a>
</p>

---

### What is Matoi?

**Matoi** is an AI-native project management tool built for developers, teams, and builders who want to spend less time managing work and more time doing it.

Named after the Edo-era fire brigade banner — a rallying signal planted atop buildings to tell everyone: *help has arrived, the team is here* — Matoi brings that same clarity to modern project management.

Describe a goal in plain language. Matoi breaks it down into tasks, estimates effort, maps dependencies, assigns work based on team capacity, and generates status updates from your actual commits and PRs. No templates. No ceremony.

### How it works

```
$ matoi plan "Ship user auth with OAuth + MFA by Friday"

→ Analyzing scope...
✓ 8 tasks created across 3 workstreams
  ├─ OAuth provider integration    (Sarah, 3d)
  ├─ MFA flow + recovery codes     (James, 2d)
  ├─ Session management refactor   (Sarah, 1d)
  └─ E2E tests + security audit    (Kai, 2d)
⚠ 1 risk: MFA depends on OAuth — parallel track possible
✓ Team notified · Sprint board updated
```

### Core capabilities

| | Feature | What it does |
|---|---|---|
| 🧠 | **AI task breakdown** | Describe goals naturally → get structured, assigned, estimated tasks |
| 🔄 | **Intelligent sprints** | Learns velocity, predicts blockers, rebalances workloads |
| 📡 | **Context-aware updates** | Auto-generates standups from commits, PRs, and conversations |
| ⌨️ | **CLI-first** | Full project management from your terminal |
| 👥 | **Team pulse** | Real-time visibility into workload, blockers, and momentum |
| 🔗 | **40+ integrations** | GitHub, GitLab, Slack, Linear, Jira, and more |

### Repositories

| Repository | Description |
|---|---|
| [`matoi-landing`](https://github.com/matoi-dev/matoi-landing) | Landing page — [matoi.dev](https://matoi.dev) |
| [`matoi-app`](https://github.com/matoi-dev/matoi-app) | Core application |
| [`matoi-cli`](https://github.com/matoi-dev/matoi-cli) | Command-line interface |
| [`matoi-sdk`](https://github.com/matoi-dev/matoi-sdk) | Developer SDK & API client |
| [`matoi-docs`](https://github.com/matoi-dev/matoi-docs) | Documentation site |
| [`matoi-integrations`](https://github.com/matoi-dev/matoi-integrations) | Official integration plugins |

### Get involved

Matoi is currently in **early access**. Here's how to get started:

- **Join the waitlist** → [matoi.dev](https://matoi.dev)
- **Follow development** → Star this org and watch our repos
- **Join the community** → [Discord](https://discord.gg/matoi)
- **Report issues** → Open an issue in the relevant repo
- **Contribute** → Check `CONTRIBUTING.md` in each repo for guidelines

### Stack

Built with TypeScript, React, Node.js, and PostgreSQL. AI powered by a custom orchestration layer. Deployed on edge infrastructure for speed everywhere.

---

<p align="center">
  <sub>纏 · Rally. Build. Ship.</sub>
</p>
