## Finance & Investment | AI-assisted Financial Systems

I design and build production financial applications using AI-assisted development, with a strong focus on financial logic, data flows, APIs, accounting workflows and model evaluation.

- 🎓 Master's degree in Audit & Finance
- 📊 Finance, accounting, treasury and financial analysis — French GAAP (PCG), VAT, financial statements, cash management
- 📈 Markets and digital assets — equities, futures, crypto spot and perpetuals, DeFi
- 🛠️ Building production financial applications with AI-assisted development
- 🔌 APIs, financial data, automation and analytics

---

### Selected work

**[Multi-account Financial Dashboard](https://github.com/fabolousfab7/financial-portfolio-dashboard-showcase)** · *public showcase, demo data* · [live demo](https://fabolousfab7.github.io/financial-portfolio-dashboard-showcase/)
Consolidates broker, crypto-exchange and bank accounts of a holding company into one EUR view. Deterministic FIFO P&L, historical FX applied per leg, IBKR Flex XML parsing, Kraken Spot/Futures, bank reconciliation, French VAT returns and AI invoice extraction with rule-based verification. 69 tests; the engine reproduces the broker's own realized P&L to the cent.
`TypeScript` `React` `Express` `PostgreSQL` `Supabase` `Recharts` `Vercel`

**[HyperArena](https://hyperarena.trade)** · *live product* · [case study](https://github.com/fabolousfab7/hyperarena-case-study)
On-chain trading performance platform built on Hyperliquid data: cash-flow-adjusted ROI, daily-return Sharpe, drawdown and consistency metrics, a composite trader score, league and division competitions, and ledger-based anti-cheat rules.
`Next.js` `TypeScript` `Prisma` `Supabase` `viem` `Anthropic API`

**Retail financial & operations dashboard** · *private, business data*
Management dashboard for a retail business, consolidating data from its business tools into financial and operational reporting. Source and data remain private.

---

### How I work with AI

I use AI to accelerate implementation while owning the specification and the verification. In practice, that means defining what each figure must mean, recomputing it independently, and catching outputs that look plausible but are wrong: currency effects ignored, derivatives valued at notional, fees deducted twice, silent zero fallbacks, tax treatments that are "usually" right.

I wrote up the recurring failure patterns here: [Evaluating model output in financial workflows](https://github.com/fabolousfab7/financial-portfolio-dashboard-showcase/blob/main/docs/AI-EVALUATION.md).

### Toolkit

**Finance** · accounting & bookkeeping · VAT · treasury · financial statement analysis · audit · P&L attribution · FX · derivatives
**Data & engineering** · TypeScript · React · Next.js · Node / Express · PostgreSQL · Supabase · Prisma · REST APIs · XML / CSV parsing · Vercel
**AI** · AI-assisted development · LLM output evaluation · document extraction with verification

### Other

- [technocore-windows-beginner-guide](https://github.com/fabolousfab7/technocore-windows-beginner-guide) — bilingual (EN/FR) guide to cryptographic identity setup and key hygiene on Windows
