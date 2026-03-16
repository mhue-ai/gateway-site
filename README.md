# ClawPurse Gateway Site

Static website for the [ClawPurse x402 Gateway](https://gateway.clawpurse.ai) — an x402-compatible HTTP 402 micropayment gateway for AI agents, DePIN operators, and machine-to-machine commerce on the Neutaro blockchain.

## Live

**[gateway.clawpurse.ai](https://gateway.clawpurse.ai)**

## What is this?

This repo contains the static HTML site for the ClawPurse 402 Gateway documentation, including:

- Payment flow diagrams (pay-per-request and prepaid balance)
- API endpoint reference
- Agent integration examples (Python and TypeScript)
- Quick start guide
- Configuration reference
- FAQ

The gateway itself (the actual server code) lives at [github.com/mhue-ai/clawpurse-gateway](https://github.com/mhue-ai/clawpurse-gateway).

## i18n

The site is available in 8 languages:

| Language | Path |
|----------|------|
| English | `/en/` |
| Japanese | `/ja/` |
| Korean | `/ko/` |
| Spanish | `/es/` |
| French | `/fr/` |
| Hindi | `/hi/` |
| Chinese | `/zh/` |
| Indonesian | `/id/` |

Root `index.html` detects browser language and redirects to the appropriate version.

## Deployment

Static site hosted on GitHub Pages behind Cloudflare:

1. Push to `main` branch
2. GitHub Pages deploys from root
3. Cloudflare DNS points `gateway.clawpurse.ai` → GitHub Pages
4. No build step required

## Part of the ClawPurse Ecosystem

| Site | Description |
|------|-------------|
| [clawpurse.ai](https://clawpurse.ai) | NTMPI agentic wallet with encrypted keystores, guardrails, and staking |
| [gateway.clawpurse.ai](https://gateway.clawpurse.ai) | x402-compatible HTTP 402 micropayment gateway (this site) |
| [drip.clawpurse.ai](https://drip.clawpurse.ai) | Agent-friendly NTMPI faucet with proof-of-work |
| [ledger.clawpurse.ai](https://ledger.clawpurse.ai) | Neutaro wallet explorer and IRS tax estimator |
| [get.clawpurse.ai](https://get.clawpurse.ai) | One-click NTMPI acquisition portal |
| [clawpurse.ai/x402](https://clawpurse.ai/x402/) | x402 on Cosmos explainer |

## License

MIT — Copyright (c) 2026 Mhue AI
