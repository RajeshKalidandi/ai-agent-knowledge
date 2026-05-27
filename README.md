# ai-agent-knowledge

> **From trending noise to curated intelligence.**  
> Autonomous daily ingestion system that discovers, scores, and documents AI tools relevant to Rajesh's stack.

## Structure

```
skills/
├── coding-agents/     — Claude Code, OpenCode, Codex, Hermes, OpenClaw, Copilot, Devin
├── app-builders/      — Bolt.new, v0, Lovable, Replit Agent, Cursor
├── frameworks/        — LangGraph, AutoGen, CrewAI, AntiGravity, Mastra
├── infrastructure/    — Supabase, Redis, Ollama, OpenRouter, Vercel
├── model-providers/   — OpenAI, Anthropic, Google, xAI, Mistral
daily/                 — Daily activity logs (timestamped)
weekly/                — Weekly summaries and trend analysis
monthly/               — Monthly ecosystem snapshots
stats/                 — Machine-readable trend data (JSON)
```

## Scoring System

```
Score = stars * 0.35
      + weeklyGrowth * 0.30
      + ecosystemMentions * 0.15
      + repoAgeFactor * 0.10
      + personalRelevance * 0.10
```

Where `personalRelevance` is based on Rajesh's stack:  
**Next.js · TypeScript · AI/LLMs · Supabase · Vercel · Python · React**

## How It Works

1. **Observe** — Scan GitHub trending across AI agent categories
2. **Score** — Rank by formula + personal stack relevance
3. **Curate** — Star top-scored repos (not just trending)
4. **Learn** — Write SKILL.md docs for new tools discovered
5. **Store** — Commit daily logs, weekly trends, monthly snapshots
6. **Report** — Deliver summary to Telegram

Built by [RajeshKalidandi](https://github.com/RajeshKalidandi) · Powered by Hermes Agent
