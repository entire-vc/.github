# Toolbox for AI-native builders

Open-source tools that connect your knowledge base, AI agents, and team — into repeatable workflows.

Obsidian is our first integration layer. The platform goes wider: agent marketplace, MCP gateway, unified credits, team collaboration.

| Layer | Product | What it does | Links |
|-------|---------|-------------|-------|
| **Sync** | [Local Sync](https://github.com/entire-vc/evc-local-sync-plugin) | Bidirectional sync between Obsidian vault and AI dev tools (Claude Code, Cursor, VS Code) | [Install](https://obsidian.md/plugins?id=evc-local-sync) |
| **Collaboration** | [Team Relay](https://github.com/entire-vc/evc-team-relay) | Self-hosted real-time collaboration server for Obsidian. Includes web publishing | [Docker](https://github.com/entire-vc/evc-team-relay#quick-start) |
| **Collaboration** | [Team Relay Plugin](https://github.com/entire-vc/evc-team-relay-obsidian-plugin) | Obsidian plugin for live team editing via Team Relay | [Install](https://obsidian.md/plugins?id=evc-team-relay) |
| **AI Agents** | [OpenClaw Skill](https://github.com/entire-vc/evc-team-relay-openclaw-skill) | REST API skill — let AI agents read/write Obsidian notes in real-time | [Setup](https://github.com/entire-vc/evc-team-relay-openclaw-skill#readme) |
| **AI Agents** | [Spark MCP](https://github.com/entire-vc/evc-spark-mcp) | MCP server for the Spark workflow catalog. Use with Claude, ChatGPT, any MCP client | `npx evc-spark-mcp` |

## What's Live & Coming

- **[Spark](https://spark.entire.vc)** — your AI toolbox for real work. Agents, skills, prompts, bundles and MCP connectors — find, share and monetize AI tools. Already live!
- **MCP Gate** — unified gateway to multiple MCP servers with metering and credits

## Quick Start

**Local Sync** — sync vault ↔ local folders (2 min):
```
# Obsidian → Community Plugins → search "EVC Local Sync" → Install
```

**Team Relay** — self-hosted team collaboration (5 min):
```bash
git clone https://github.com/entire-vc/evc-team-relay
cd evc-team-relay && docker compose up -d
```

**Spark MCP** — AI tool integration (1 min):
```bash
npx evc-spark-mcp
```

## Who This Is For

- **Solo builders** — sync your vault with AI coding tools, keep context in one place
- **Small teams (2–20)** — collaborative knowledge base in Obsidian, no SaaS lock-in
- **AI-native developers** — agent access to your notes, MCP integrations, workflow automation

## Community

- 🌐 [entire.vc](https://entire.vc)
- 💬 [Telegram](https://t.me/entire_vc)
- 📧 in@entire.vc

## Contributing

Every repo has its own guide. General flow: Fork → Branch → PR. We use conventional commits.

## License

MIT or Apache 2.0 — check individual repos.

---

*Built by [Entire VC](https://entire.vc) — toolbox for builders who ship.*
