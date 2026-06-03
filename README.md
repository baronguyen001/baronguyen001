# Hey, I'm Baro 👋

**I build AI-automation tools that ship — and I'm packaging them so you can ship too.**

The pattern behind every monitoring/alerting bot is the same: scrape a source → rank or summarize with AI → alert you → run on a schedule. I run this stack across crypto signals, on-chain cluster detection, and OSS bounty hunting — and I'm turning it into tools you can pick up.

## 🚀 Build automation bots with Claude

- **[ai-automation-skills](https://github.com/barobaonguyen/ai-automation-skills)** *(v0.2.0 — live)* — 15 production-tested Claude Code skills for the scrape → AI → alert stack: Gemini cost control + prompt caching + structured output, Telegram alerts, cron scheduling, resumable pipelines, IMAP email digests, walk-forward validation + backtest comparison, OSS bounty + GitHub-label scouting. One command:
  `/plugin install ai-automation-skills@barobaonguyen`
- **Trawlkit** *(shipping soon)* — a paid starter kit that wires these skills into runnable Python bots: Playwright scraper + cost-controlled Gemini + Telegram alerts + scheduler + a `tk` CLI + 3 working bots. Follow [@barobaonguyen](https://x.com/barobaonguyen) for launch.

## 🔬 Built and battle-tested

- **[gemini-agent-toolkit](https://github.com/barobaonguyen/gemini-agent-toolkit)** *(v0.1.0 — live)* — Gemini-native agent framework. Cost tracking, prompt caching, structured output. 88% test coverage, CI on 3.11/3.12 × Ubuntu/Windows.
- **[gemini-cookbook](https://github.com/barobaonguyen/gemini-cookbook)** *(v0.2.0 — live)* — 10 runnable `google-genai` recipes, no abstraction layer: prompt caching, structured output, batch API, cost tracking, thinking budget, function calling, search grounding, Files API, multimodal vision, embeddings. CI on 3.11/3.12 × Ubuntu/Windows.
- **[playwright-cloudflare](https://github.com/barobaonguyen/playwright-cloudflare)** *(v0.2.0 — live)* — Playwright stealth defaults for authorized browser testing: explicit sync helpers, `pw-stealth check`, opt-in fingerprint profiles, and no extra stealth dependency. CI on 3.11/3.12 × Ubuntu/Windows.
- **[ai-news-aggregator](https://github.com/barobaonguyen/ai-news-aggregator)** *(v0.1.0 — live)* — Auto-summarize 35+ AI newsletters into one weekly Telegram digest. Gmail IMAP → Gemini classify + summarize → Telegram. ~$0.02/week on Gemini Pro, runs Sunday 8AM via cron.
- **[ideas-vault-kit](https://github.com/barobaonguyen/ideas-vault-kit)** *(v0.1.0 — live)* — A 4-pillar /40 scoring workflow to kill 9 of every 10 side-project ideas before you write a line of code.

## 📊 Crypto / on-chain (proof it runs at scale)

- **confluence-scanner** *(shipping soon)* — Walk-forward-first confluence scorer: TA + on-chain + funding. The framework that rejects my own bad strategies.
- **wallet-cluster-detector** *(shipping soon)* — Detect wallet clusters buying the same token within minutes. Helius + DexScreener pipeline.

## Working with me

Available for AI-agent / LLM integration, data pipelines, and scraping/automation work.
Reach me: [@barobaonguyen](https://x.com/barobaonguyen) on X

Build-in-public threads on cost optimization, walk-forward validation, and shipping small products. See pinned tweet 👇
