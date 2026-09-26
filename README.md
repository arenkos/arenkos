# Hi, I'm Aren 👋

**Software engineer · AI-native development · Istanbul, Türkiye**

I build products end to end and run the infrastructure they sit on — from Python, Node.js and Swift application code through to the pipelines, containers and monitoring that keep them in production. Writing software since 2015, shipping independent products since 2020, and currently operating 15–20 production applications on infrastructure I manage myself.

Most of my code lives in private repositories because it belongs to products and clients. This page links to the live products instead.

---

## 🤖 How I work with coding agents

Coding agents are my primary tool across planning, implementation, testing, refactoring and documentation — on real production work.

- **Claude Code as daily driver**, running on my own VPS with isolated per-project configurations so parallel sessions work across separate codebases without collisions.
- **Agent output is reviewed like an untrusted pull request.** The failures I catch most often are confident assumptions about code the agent never read, and silently dropped edge cases. I make the agent state its assumptions and its plan before it writes anything.
- **Docs and conventions as agent infrastructure.** READMEs, commit conventions and repository docs are written so agents perform well against them, not only for human readers.
- **Validation over trust.** Where model output reaches customers, a deterministic or model-based gate sits in front of it.

---

## 🛠️ Selected products

| Product | What it is | Stack |
|---|---|---|
| [**AR Code Editor**](https://code.aryazilimdanismanlik.com) | Browser-based code editor with an integrated AI agent. Open a local project or connect a GitHub repo; editing and builds run server-side, so it works from anywhere. | JavaScript, Node.js, LLM APIs |
| [**CVision**](https://cvision.aryazilimdanismanlik.com) | CV platform with LLM-backed parsing of uploaded CVs, translation, cover-letter generation and photo enhancement. | Python, JavaScript, LLM APIs |
| [**Permio**](https://permio.app) | Crypto trading platform: backtesting engine over 4 years of market data and automated strategy execution against the Binance API, with native mobile clients. | Python, Swift, Kotlin |
| [**Yönetil.io**](https://yonetilio.com) | Multi-tenant property management platform: dues accounting, announcements and resident communication. | PHP, JavaScript, SQL |
| [**QAR Menu**](https://qarmenu.shop) | QR ordering and menu platform for cafés and restaurants. | PHP, JavaScript, SQL |
| [**AR Haber**](https://armedia.live) | News platform with web and mobile clients, fed by an automated n8n pipeline that generates video with Gemini, Google TTS and fal.ai and publishes to Instagram, Facebook and YouTube Shorts. | n8n, Swift, JavaScript |
| [**biofol.io**](https://biofol.io/arsoft) | Link management and short-link system I built and run. | PHP, JavaScript |

More projects on [aryazilimdanismanlik.com](https://aryazilimdanismanlik.com).

---

## 💼 Currently

**Backend & platform engineering** on a multi-tenant .NET and SQL Server service platform:

- LLM-based services — log classification in production, and a validation layer (in development) that audits another system's output before it reaches customers
- An internal service monitoring platform, built end to end (React, Node.js, .NET, SQL Server)
- CI/CD with automated semantic versioning and changelog generation — releases went from hours of manual work to an automated run of under 20 minutes

---

## 🧰 Tech

**Core:** Python · JavaScript / TypeScript · PHP · SQL · Swift
**Also:** C# / .NET 8 · Java · Kotlin · Objective-C · C/C++ · Go (learning)
**Backend & data:** FastAPI · Node.js · REST · SQL Server · MySQL · DuckDB
**Front end & mobile:** React · Vite · Tailwind · iOS · Android
**Infrastructure:** Docker · Azure · Azure DevOps CI/CD · Ubuntu & Windows Server · nginx · Caddy · pm2
**AI:** Claude Code · Claude & Gemini APIs · local LLMs · n8n agentic workflows

---

## 📫 Contact

[LinkedIn](https://linkedin.com/in/arenkos) · [info@aryazilimdanismanlik.com](mailto:info@aryazilimdanismanlik.com) · [aryazilimdanismanlik.com](https://aryazilimdanismanlik.com)
