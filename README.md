# Hey, I'm Baro 👋

**I build AI-automation tools that ship — and I'm packaging them so you can ship too.**

The pattern behind every monitoring/alerting bot is the same: scrape a source → rank or summarize with AI → alert you → run on a schedule. I run this stack across crypto signals, on-chain cluster detection, and OSS bounty hunting — and I'm turning it into tools you can pick up.

## 🚀 Build automation bots with Claude

- **[ai-automation-skills](https://github.com/baronguyen001/ai-automation-skills)** *(v0.2.0 — live)* — 15 production-tested Claude Code skills for the scrape → AI → alert stack: Gemini cost control + prompt caching + structured output, Telegram alerts, cron scheduling, resumable pipelines, IMAP email digests, walk-forward validation + backtest comparison, OSS bounty + GitHub-label scouting. One command:
  `/plugin install ai-automation-skills@baronguyen001`
- **Trawlkit** *(shipping soon)* — a paid starter kit that wires these skills into runnable Python bots: Playwright scraper + cost-controlled Gemini + Telegram alerts + scheduler + a `tk` CLI + 3 working bots. Follow [@barobaonguyen](https://x.com/barobaonguyen) for launch.

## 🔬 Built and battle-tested

- **[gemini-agent-toolkit](https://github.com/baronguyen001/gemini-agent-toolkit)** *(v0.2.0 — live)* — Gemini-native agent framework. Streaming, Google Search grounding helper, cost tracking, prompt caching, structured output. 86% test coverage, CI on 3.11/3.12 × Ubuntu/Windows.
- **[gemini-cookbook](https://github.com/baronguyen001/gemini-cookbook)** *(v0.2.0 — live)* — 10 runnable `google-genai` recipes, no abstraction layer: prompt caching, structured output, batch API, cost tracking, thinking budget, function calling, search grounding, Files API, multimodal vision, embeddings. CI on 3.11/3.12 × Ubuntu/Windows.
- **[playwright-cloudflare](https://github.com/baronguyen001/playwright-cloudflare)** *(v0.2.0 — live)* — Playwright stealth defaults for authorized browser testing: explicit sync helpers, `pw-stealth check`, opt-in fingerprint profiles, and no extra stealth dependency. CI on 3.11/3.12 × Ubuntu/Windows.
- **[ai-news-aggregator](https://github.com/baronguyen001/ai-news-aggregator)** *(v0.1.0 — live)* — Auto-summarize 35+ AI newsletters into one weekly Telegram digest. Gmail IMAP → Gemini classify + summarize → Telegram. ~$0.02/week on Gemini Pro, runs Sunday 8AM via cron.
- **[ideas-vault-kit](https://github.com/baronguyen001/ideas-vault-kit)** *(v0.1.0 — live)* — A 4-pillar /40 scoring workflow to kill 9 of every 10 side-project ideas before you write a line of code.
- **[walk-forward-validator](https://github.com/baronguyen001/walk-forward-validator)** *(v0.1.0 — live)* — Train/validation splitter for time-series strategy tuning: catch overfit before it reaches production. Leak-tested, CI on 3.11/3.12 × Ubuntu/Windows.

## 📊 Crypto / on-chain (proof it runs at scale)

- **[confluence-scanner](https://github.com/baronguyen001/confluence-scanner)** *(v0.1.0 — live)* — Walk-forward-first confluence scorer: TA + on-chain + funding. The framework that rejects my own bad strategies. Package `confscan`, CI on 3.11/3.12 × Ubuntu/Windows.
- **[wallet-cluster-detector](https://github.com/baronguyen001/wallet-cluster-detector)** *(v0.1.0 — live)* — Detect wallet clusters buying the same token within minutes. Helius + DexScreener pipeline, score-weighted detector, paper-trade simulator. Package `clusterdetect`.
- **[helius-rate-limiter](https://github.com/baronguyen001/helius-rate-limiter)** *(v0.1.0 — live)* — Survive the Helius free tier: RPS limiter + monthly-quota budget + circuit breaker + multi-key rotation. Sync, stdlib-only, zero deps.
- **[pinescript-strategy-template](https://github.com/baronguyen001/pinescript-strategy-template)** *(v0.1.0 — live)* — Parameterized Pine v6 strategy template + a Python next-open-fill backtest engine with walk-forward replay/optimize and a TradingView "List of Trades" CSV parser. Package `pinescript-walkforward`.

## Working with me

Available for AI-agent / LLM integration, data pipelines, and scraping/automation work.
Reach me: [@barobaonguyen](https://x.com/barobaonguyen) on X

Build-in-public threads on cost optimization, walk-forward validation, and shipping small products. See pinned tweet 👇
