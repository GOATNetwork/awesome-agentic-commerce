# 🤖 Awesome Agentic Commerce

**The future of commerce isn't clicks — it's agents.**

Users no longer browse and buy.  
They delegate **intent** to autonomous AI agents that search, compare, negotiate, transact, optimize, and even handle post-purchase logistics — all without human intervention.

This repository is a **community-driven, living collection** of:
- Wild ideas & visionary concepts
- Battle-tested best practices
- Agent architectures & patterns
- Tools, frameworks & protocols
- Real-world experiments & case studies

Whether you're a builder, researcher, founder, or just someone with a crazy-good idea for agentic commerce — this is your home.

---

## 📋 Table of Contents
- [What is Agentic Commerce?](#what-is-agentic-commerce)
- [Core Ideas & Patterns](#core-ideas--patterns)
- [Best Practices](#best-practices)
- [Tools & Frameworks](#tools--frameworks)
- [Case Studies & Real-World Examples](#case-studies--real-world-examples)
- [Open Challenges & Research Directions](#open-challenges--research-directions)
- [Contributing](#contributing)
- [License](#license)

---

## What is Agentic Commerce?

Agentic commerce is the shift from **"human-in-the-loop"** e-commerce to **"agent-in-the-loop"** commerce:

- Personal shopping agents that understand your taste, budget, values, and schedule
- Negotiation agents that haggle in real time across multiple marketplaces
- Supply-chain agents that autonomously reorder, reroute, and optimize inventory
- Multi-agent marketplaces where seller agents and buyer agents negotiate directly
- Autonomous checkout, fraud detection, returns, and loyalty programs

Think: “Buy me the best noise-cancelling headphones under $300 that ship in 2 days” → agent does everything.

---

## Core Ideas & Patterns

(Share your architectural patterns, agent swarms, memory systems, tool-use strategies, etc.)

- **Intent → Agent Delegation Pattern** – How to turn vague user intent into executable agent workflows
- **Multi-Agent Negotiation Protocols** – Buyer vs Seller vs Marketplace agents
- **Trust & Verification Layers** – How agents prove they actually got the best deal
- **Memory & Personalization Loops** – Long-term user preference agents
- **[Add your idea here via PR!](#contributing)**

---

## Best Practices

(Real lessons from production or serious prototypes)

- Prompt engineering for commerce agents
- Tool-calling & API orchestration strategies
- Error handling & fallback mechanisms in autonomous transactions
- Privacy-preserving agent design
- Cost & latency optimization for high-volume agent runs
- **[Add your best practice here via PR!](#contributing)**

---

## Tools & Frameworks

(Feel free to add new entries)

- **LangGraph / LangChain** – Agent orchestration
- **AutoGen / CrewAI / MetaGPT** – Multi-agent collaboration
- **Camel-AI** – Role-playing agent frameworks
- **OpenAI Swarm** – Lightweight multi-agent orchestration
- **Anthropic Computer Use** + commerce APIs
- **Blockchain / Payment agents** (Crossmint, Stripe Agents, etc.)
- **Protocol layer** (e.g. Agentic Commerce Protocol proposals)
- **[Add your favorite tool here via PR!](#contributing)**

---

## Case Studies & Real-World Examples

### Consumer-Facing Agentic Commerce

- **OpenAI Instant Checkout + ACP in ChatGPT** — Users describe what they want, the agent researches across the web, surfaces products from Etsy/Shopify merchants (Glossier, SKIMS, Spanx, etc.), and completes the full purchase *inside the chat* via Stripe-powered Instant Checkout. No redirects needed. OpenAI open-sourced the [Agentic Commerce Protocol (ACP)](https://openai.com/index/agentic-commerce-protocol/) for broader adoption.
- **Google Gemini "Buy for Me" / Agentic Checkout (UCP)** — Describe needs in plain language, and the agent searches Walmart, Wayfair, Target, Shopify, etc., checks real-time inventory/pricing/loyalty offers, and executes purchases with Google Pay. Includes price tracking + auto-buy triggers. Powered by the [Universal Commerce Protocol (UCP)](https://developers.google.com/commerce/universal-commerce-protocol).
- **Walmart + Google Gemini Full Shopping Experience** — Walmart co-developed the UCP open standard with Shopify, Etsy, Target, and Wayfair. End-to-end shopping (discovery → comparison → basket → checkout) entirely inside Google Gemini. Walmart's internal "Sparky" shopper agent handles real-time inventory and predictive logistics.
- **Perplexity "Buy with Pro" (PayPal-powered)** — Pro users get AI search → personalized recommendations → one-click in-chat checkout directly in Perplexity (or its Comet browser). PayPal handles payments/merchant-of-record duties; free shipping on eligible orders. High-intent shopping flow with memory of past searches.
- **Crossmint Telegram Shopping Agents** — Text a need in Telegram, the agent autonomously searches, compares options across catalogs, presents matches, and completes checkout with one tap (credit card, ACH, or stablecoins). Deployed live for various merchants; setup in under an hour.
- **Anthropic Claude as AI Travel Agent (Crossmint MCP)** — Natural-language conversation to research, compare, and book flights autonomously via Crossmint payments (USDC on Solana or cards). Live and working today.
- **Flight Deal Sniper Agents (Crossmint-powered)** — Set criteria (e.g., "NYC–London under $400, max 1 stop"). The agent monitors 100+ daily price changes across platforms 24/7 and auto-purchases when thresholds are met. Fully autonomous deal execution.
- **Amazon Rufus AI Shopping Assistant** — Conversational agent inside the Amazon app/site that researches products, answers complex queries, and drives purchases. Users who engage with Rufus are ~60% more likely to buy and convert at nearly 4× the rate of non-users.

### Merchant & Operations Agents

- **Walmart Agentic Super Agents (Inventory + Operations)** — Includes "Marty" supplier agent, autonomous inventory agents using computer vision/shelf sensors that trigger restocking with zero human steps, and predictive shipping agents that forward-deploy stock before orders arrive. Pilot results: 30% fewer stockouts; 30% faster same-day delivery.
- **Sephora Digital Beauty Consultant** — In-store/app agents scan skin tone/products and autonomously suggest routines + virtual try-ons with real-time personalization.
- **H&M Agentic Layout & Virtual Assistant** — Tracks foot traffic/purchases and auto-optimizes store merchandising while handling shopping/returns. Results: 17–25% basket size/conversion lifts.
- **eBay Mercury Platform** — Real-time personalized shopping guidance and recommendation agents that act across browsing sessions.

### Protocols & Infrastructure

- **[OpenAI Agentic Commerce Protocol (ACP)](https://openai.com/index/agentic-commerce-protocol/)** — Open protocol enabling AI agents to discover, compare, and transact with merchants
- **[Google Universal Commerce Protocol (UCP)](https://developers.google.com/commerce/universal-commerce-protocol/)** — Open standard co-developed with Walmart, Shopify, Etsy, Target, and Wayfair for agent-driven commerce
- **[x402 Payment Protocol](https://www.x402.org/)** — HTTP-native micropayment protocol using the `402 Payment Required` status code, enabling agents to pay for API calls, content, and services programmatically with stablecoins — no API keys or subscriptions needed
- **Machine Payments / Autonomous Agent Wallets** — Infrastructure for machine-to-machine payments where AI agents hold wallets, authorize transactions, and settle payments autonomously (e.g., Crossmint agent wallets, Coinbase AgentKit, Stripe agent payments)

- **[Add your case study or experiment here via PR!](#contributing)**

---

## Open Challenges & Research Directions

- How do agents handle conflicting user preferences across family members?
- Legal & liability questions when an agent buys the wrong thing
- Cross-platform identity and agent reputation systems
- Preventing agent spam / price manipulation in marketplaces
- Energy & cost efficiency at scale
- **[Add your open question or research idea here via PR!](#contributing)**

---

## Contributing

**This repo is only as good as the community makes it.**

We love:
- New ideas (even half-baked ones)
- Best practices from real builds
- Tools, papers, demos, or GitHub repos
- Fixes, improvements, or translations

### How to contribute in 2 minutes:
1. Fork the repo
2. Edit this README (or create a new Markdown file in the appropriate folder)
3. Add your entry in the right section with a short description + link
4. Open a Pull Request with a clear title

**Example PR title:** `feat: add "Hierarchical Negotiation Agent Swarm" pattern`

Not sure where it fits? Open an Issue or Discussion — we’ll help!

[CONTRIBUTING.md](CONTRIBUTING.md) has the full template and guidelines.

---

## Star History & Community

[![Telegram](https://img.shields.io/badge/Telegram-Join%20Chat-blue?logo=telegram)](https://t.me/goatbuilderhub) [![Telegram](https://img.shields.io/badge/@clawup-Join%20Channel-blue?logo=telegram)](https://t.me/clawup)

[![Star History Chart](https://api.star-history.com/svg?repos=GOATNetwork/awesome-agentic-commerce&type=Date)](https://star-history.com/#GOATNetwork/awesome-agentic-commerce&Date)

**Made with ❤️ by the agentic commerce community**

---

## License

This repository is licensed under the [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (CC0) — feel free to use anything here for your own projects.

---

**Ready to shape the future of commerce?**  
🛠️ **Build your first agent today** — pick a pattern from [Core Ideas](#core-ideas--patterns), grab a tool from [Frameworks](#tools--frameworks), and ship it.  
Then drop your experiment in a PR and join the community on [Telegram](https://t.me/goatbuilderhub)! 🚀
