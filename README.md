# 🚀 LP Scoring API — n8n + Gemini 3 Pro

The flagship workflow of this repository.
A production-ready, API-first landing page analysis engine powered by n8n + LLM reasoning.

Built publicly by Yusuke (@yskautomation) — AI Automation Architect.

---

# 🔥 Why This Workflow Matters

Most landing-page graders are UI toys.
This one is not.

This workflow is designed as infrastructure:

- API-first
- Headless / machine-readable
- Perfect for n8n, Make, Zapier, or your SaaS backend
- Multi-purpose: monitoring, CRO, competitor analysis, ICP inference
- Uses Gemini 3 Pro for high-accuracy reasoning
- Returns strict, validated JSON (no hallucinated formatting)

👉 This is the core engine I’m building my micro-SaaS ecosystem on.
And now you can use it too.

---

# 🎯 What the LP Scoring API Does

Submit a URL → get a complete structured evaluation:

- Target audience inference
- Offer summary
- Primary unique value
- Strengths & weaknesses
- Competitor types
- Differentiation analysis
- Conversion, clarity, relevance, trust scores
- Quick wins (1–2 day fixes)
- A/B test ideas
- Overall score (0–100)
- Confidence levels
- Full metadata

All delivered as a single clean JSON object, ready for:

- dashboards
- Slack alerts
- email reports
- CI/CD checks
- competitive intelligence
- automated CRO pipelines

---

# 📦 Download the Workflow

## 🔍 LP Scoring API (Gemini 3 Pro)

➡️ lp-scoring-api.json  
An API-first landing page analysis engine for SaaS + B2B.

Just import + add OpenRouter creds — ready in minutes.

---

# ⚙️ How It Works (High-Level)

1. POST a URL to /lp-scoring
2. Workflow fetches & cleans the website HTML
3. Constructs a strict JSON-returning prompt
4. Sends to Gemini 3 Pro via OpenRouter
5. Parses, validates, and normalizes the response
6. Returns a clean, predictable JSON payload

Everything is headless — no UI, no manual review.

---

# 🔧 Ideal Use Cases

This engine is designed for developers, founders, agencies, and automation builders who want:

- Daily LP monitoring (competitors or clients)
- Slack alerts if clarity/CTA/trust drops
- Automated CRO suggestions
- ICP detection pipelines
- Data-driven A/B testing
- Bulk LP auditing (100–1,000 sites per month)
- Backend API for SaaS products

---

# 🧱 Example Integrations

- n8n → Score competitor LPs every morning → Slack
- Make.com → Summaries to Google Sheets
- Zapier → Alert when overall score drops below 70
- Supabase → Store results & build a dashboard
- Your SaaS → “LP Analyzer” feature powered by this API

---

# 🌐 Other Workflows in This Repo

While LP Scoring API is the flagship, the repo also includes:

## 🧠 Self-Reflecting Logger
AI-analyzed n8n execution logs

## 🔍 GitHub Workflow Finder AI
Discover public n8n workflows

## 💬 Empathy Reply Assistant
Emotionally-aware reply generator

## 🎨 Creator RAG Booster
Learns your writing tone from examples

---

# 🏗️ Author

**Yusuke Matsuba — AI Automation Architect**

Building API-first, headless automation systems with:

- n8n
- LangChain
- Gemini 3 Pro
- OpenAI / Anthropic
- Supabase
- Google / Notion output layers

Focused on systems that earn, learn, and evolve autonomously.

---

# 📜 License

MIT License © 2025 Yusuke M.
Feel free to fork, extend, and deploy in your products.

---

⭐ If the LP Scoring API helps you, please star the repo — it boosts visibility and supports future releases.
