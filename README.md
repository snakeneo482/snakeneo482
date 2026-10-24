# Domantas Ūba

### Independent Website Auditor · Custom TradingView Pine Script

I'm an independent developer based in Lithuania. I audit websites for **security, technical SEO, performance and accessibility**. I explain what I find in plain language and help fix it.

I also write **custom TradingView indicators in Pine Script**, built around your own rules and charts, and build **Python tools for business process automation**.

[Request an audit](https://domantasuba.com) · [LinkedIn](https://www.linkedin.com/in/domuba) · [TradingView scripts](https://www.tradingview.com/u/n0x6E6F6F6E65/#published-scripts)

---

## Website audits

AI tools and page builders make it quick to launch a website. My audit checks whether the finished site is secure, fast, findable and usable.

| Area | What I check |
| --- | --- |
| **Security** | HTTPS/TLS, security headers, exposed files and endpoints, safe defaults. Passive checks only, not a penetration test. |
| **Technical SEO** | Indexing, sitemap and robots.txt, titles and descriptions, structured data, broken links, redirects |
| **Performance** | Google Lighthouse lab tests on phone and desktop, image weight, render-blocking and unused code |
| **Accessibility** | Automated WCAG checks: contrast, labels, keyboard focus, touch targets |
| **AI-built websites** | An independent review of sites made with AI or site builders, before real visitors arrive |
| **Remediation** | If needed, I fix the issues and run the audit again to confirm they are resolved |

### What you get

A clear PDF report written for people, not just developers:

- **An overall score and a score per area** (0–100), with what each one means
- **Every issue with a priority**, explaining *what I found*, *why it matters* and *what to do*
- **An action plan**: what to fix now, in the next update, and when convenient
- **A technical appendix** with evidence for your developer

### A real result

A one-page service website, October 2026 (the client is not named):

| | Before | After |
| --- | :---: | :---: |
| **Overall score** | 88 | **100** |
| Mobile speed (Lighthouse) | 66 | **96** |

What changed: security headers were added, unused URLs now redirect to the homepage, the hero image is lighter and unused scripts were removed, the sitemap was fixed, and structured data and an FAQ section were added.

*Scores are lab measurements from my audit at the time of testing. An audit cannot guarantee search rankings.*

---

## Featured projects

### [REGIME · Market Regime](https://github.com/builtbyuba/MarketRGM)

**A compact TradingView dashboard for understanding market conditions.**

REGIME brings trend direction, strength, volatility and momentum into one view. It identifies **Bull, Bear, Range and Transition** states and places them beside confirmed higher-timeframe context, so you can see how the current chart relates to the broader market.

- **Confirmed-candle updates** for the local regime and completed higher-timeframe context.
- **ADX, ATR% and RSI** summarize trend strength, volatility and momentum.
- **Regime history and transition markers** show how conditions develop over time.
- Built in **Pine Script v6**, with defaults designed around **BTC and ETH on 1H and 4H charts**.

[![REGIME on BTCUSDT 4H](https://raw.githubusercontent.com/builtbyuba/MarketRGM/main/assets/btc-4h.jpg)](https://github.com/builtbyuba/MarketRGM)

*Actual TradingView screenshot. REGIME describes market conditions; it does not provide buy or sell signals or promise trading results.*

[Explore REGIME →](https://github.com/builtbyuba/MarketRGM)

### [ProcessDock](https://github.com/builtbyuba/ProcessDock)

**A self-hosted Python platform that turns invoice documents into a structured review workflow.**

ProcessDock helps small businesses reduce repetitive invoice entry and checking. Upload a batch of supported text PDFs, and it separates individual invoices, extracts their fields, validates the data and routes exceptions to a review queue. Processing runs locally without AI, paid services or external APIs.

- **Batch processing:** handle multiple files and multi-invoice PDFs, including invoices spanning several pages.
- **Validation and policies:** check required fields, totals, known suppliers and duplicate identities; automatically approve valid invoices within a configured amount limit.
- **Human review:** edit, approve or reject exceptions with the original PDF pages available for reference.
- **Traceability:** follow document statuses, validation results, policy decisions and audit events.
- **CSV orders:** import valid rows, review invalid ones and export stored orders.

[![ProcessDock dashboard with synthetic demo data](https://raw.githubusercontent.com/builtbyuba/ProcessDock/main/docs/screenshots/dashboard.png)](https://github.com/builtbyuba/ProcessDock)

**Built with:** Python · FastAPI · Pydantic · SQLAlchemy · Alembic · Pandas · PyMuPDF  
**Run locally:** Docker Compose or Python 3.12+.

*Supports a documented text-PDF format. OCR and arbitrary invoice layouts are outside the current scope. The current version has no authentication and is intended for trusted local use.*

[Explore ProcessDock →](https://github.com/builtbyuba/ProcessDock)

---

## Custom TradingView Pine Script

I build indicators, dashboards, alerts and chart tools in **Pine Script v6**, and I update or fix existing scripts. Tell me your rules and I'll turn them into a clean, readable tool.

| Project | What it does | License |
| --- | --- | --- |
| [**REGIME** · Market Regime](https://github.com/builtbyuba/MarketRGM) | Market state (Bull, Bear, Range, Transition) with confirmed higher-timeframe context, ADX, ATR% and RSI in one minimal dashboard | CC BY-NC-SA 4.0 |
| [**Ichimoku Structure Pro**](https://github.com/builtbyuba/ISP) | Ichimoku with confirmed market structure and a compact multi-timeframe dashboard | CC BY-NC 4.0 |
| [**PSP** · Chart patterns](https://github.com/builtbyuba/PSP) | Chart patterns, market structure, shared 4H supply and demand zones, and EMA 200 | MIT |
| [**Rinkos Struktūra LT**](https://github.com/builtbyuba/SMCLT) | A Lithuanian-language SMC structure indicator with zones, EMA 200 and an info table | CC BY-NC-SA 4.0 |

*My indicators describe market conditions. They do not give buy or sell signals or promise trading results.*

Related tool: [**PineTester**](https://github.com/builtbyuba/PineTester), a web app for testing a supported subset of Pine Script v5 strategies against historical Binance data.

---

## Other projects

[InstaDrop](https://github.com/builtbyuba/InstaDrop) (Android, Kotlin) · [Candrivo](https://github.com/builtbyuba/Candrivo) · [ClipMind AI](https://github.com/builtbyuba/ClipMind-AI)

Each repository explains its scope, setup and license. AI tools assisted development.

**Tools I work with:** Python · JavaScript · TypeScript · Next.js · WordPress · Pine Script · Google Lighthouse · axe-core · Playwright

---

## Let's talk

Want your website checked, or need a custom indicator? Tell me what you have in mind. We agree on the scope, timeline and price before any work starts, and you work directly with me.

**Website:** [domantasuba.com](https://domantasuba.com)

**Email:** [ubadomantas@gmail.com](mailto:ubadomantas@gmail.com)

