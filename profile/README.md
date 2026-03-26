<h1 align="center">
  <img src="https://raw.githubusercontent.com/Rekko-AI/.github/main/profile/logo-dark.svg" alt="Rekko AI" height="48" />
</h1>

<p align="center">
  <strong>Prediction market intelligence for trading bots, apps, and AI agents.</strong>
</p>

<p align="center">
  <a href="https://rekko.ai">rekko.ai</a> &nbsp;|&nbsp;
  <a href="https://rekko.ai/docs">Docs</a> &nbsp;|&nbsp;
  <a href="https://discord.gg/qTPEk9aAZg">Discord</a> &nbsp;|&nbsp;
  <a href="https://x.com/RekkoAI">X / Twitter</a> &nbsp;|&nbsp;
  <a href="https://www.tiktok.com/@rekko.ai">TikTok</a>
</p>

---

Rekko AI runs multi-stage research pipelines that produce probability estimates, causal decomposition of price drivers, portfolio-aware trading signals, cross-platform arbitrage detection, and execution guidance for **Kalshi**, **Polymarket**, and **Robinhood**.

### Open Source

| Repo | Description | Install |
|------|-------------|---------|
| [**rekko-mcp**](https://github.com/Rekko-AI/rekko-mcp) | MCP server — 25 tools for Claude Code, Cursor, Windsurf | `uvx rekko-mcp` |
| [**rekko-skill**](https://github.com/Rekko-AI/rekko-skill) | OpenClaw skill for autonomous trading agents | `npx skills add Rekko-AI/rekko-skill` |
| [**docs**](https://github.com/Rekko-AI/docs) | API documentation at [docs.rekko.ai](https://rekko.ai/docs) | — |

### Get Started

```bash
# MCP server for AI coding assistants
claude mcp add rekko -- uvx rekko-mcp

# Or use the REST API directly
curl -H "Authorization: Bearer rk_free_..." https://api.rekko.ai/v1/markets
```

Get an API key at [rekko.ai/dashboard](https://rekko.ai/dashboard) — free tier available.
