<h1 align="center">AI Engineer</h1>

<p align="center">
  <em>AI agents that talk to real customers · LLM · Claude · CRM integrations</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude-191919?logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-555555" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?logo=n8ndotio&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Telegram%20Bot%20API-26A5E4?logo=telegram&logoColor=white" />
</p>

---

I build AI agents that work with live customers: they answer in messengers, qualify leads, write to the CRM and hand the conversation to a human.
AI agents (Claude Code) write most of the code. I own the architecture, the checks, security and production.

### What I build

- **AI sales agent in messengers** — qualifies leads, writes to amoCRM, hands off to a manager. Every release first runs a set of test dialogues.
- **Booking service ↔ amoCRM integration** — queue, retries, duplicate protection, rollback on failure.
- **Lead classifier for Telegram chats** — quality is measured on a reference set before each release.
- **Voice AI agent on Asterisk / FreePBX** — tested on simulated calls.
- **One-command deploys** — tests, auto-rollback, GitHub Actions, backups with restore checks.

Project details and numbers are under NDA.

### Own project

**AI seller for WhatsApp** on the official Cloud API: request signature check, prompt-injection protection, handoff to a live manager, 24 automated tests, 4–8 s reply time in tests.

### Open source

- **[n8n-multi-agent-orchestrator](https://github.com/mike-prokhorov/n8n-multi-agent-orchestrator)** — six-workflow Telegram hub: an LLM classifier routes inbound messages to small sub-agents, each with its own prompt and an audit row in Postgres.
- **[bot-monitoring-patterns](https://github.com/mike-prokhorov/bot-monitoring-patterns)** — how to keep a fleet of n8n workflows, Telegram bots and cron jobs honest: dead-man switch, monitor-of-monitors, error router.
- **[n8n-automation-templates](https://github.com/mike-prokhorov/n8n-automation-templates)** — tested n8n templates: orchestrator, voice-to-post pipeline, global error notifier, health monitor.
- **[rat-race](https://github.com/mike-prokhorov/rat-race)** — browser money game based on the Cashflow board game.

### Stack

- **LLM & agents:** Claude Code, Anthropic Claude API, OpenAI API, MCP, RAG, prompt engineering
- **Automation:** n8n, Python, Telegram Bot API, amoCRM, API integrations
- **Infra:** PostgreSQL, Docker, Linux, GitHub Actions
- **Courses:** Cisco Cybersecurity (2025), Cisco Linux (2023)

Before AI I spent 2.5 years as a design engineer in oil & gas. That is where I learned to think about what breaks next.

---

Da Nang, Vietnam (UTC+7) · write via GitHub or open an issue on any repo.
