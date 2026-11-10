# NEXORA — One platform. Local and global business finance. (browser demo v3)

Open `index.html` in Chrome or Edge. No install or server needed. Keep `assets/` next to it.

## Modules
- NEXORA AI: live assistant (Claude via API key) with a local fallback. Can pay, quote FX, read the forecast.
- NEXORA PAY: local payments, approvals, limits, protected reserve, CSV export.
- NEXORA GLOBAL: FX converter, international suppliers, cross-border payments with fee quote.
- NEXORA FLOW: 30-day cash forecast, what-if sales slider, safe-to-spend, advice.
- NEXORA BUSINESS: invoices (pay now), expenses by category, inventory with one-click reorder.
- NEXORA GUARD: risk score on every payment, duplicate / night / near-limit checks, cross-border block, protection score, alerts.

## Live AI
Click the tag above the chat, paste an Anthropic API key. The key stays in this browser's localStorage and goes only to api.anthropic.com. The AI can never approve payments, change limits, add suppliers or edit Guard.

## Honest limits
- All data is demo data in localStorage ("Reset demo data" in the sidebar).
- FX rates are fixed indicative values, not live. No bank, payment network or blockchain is connected. Nothing moves real money.
- For production: call the AI from a backend, use licensed payment partners, and add KYC/AML and exchange-control compliance.
