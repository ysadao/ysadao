<div align="center">

# Yamashita Sadao

**I ship the parts of a product that cannot be a prototype.**

Identity. Tenancy. Payments. On-chain surfaces. AI that runs on your data — not a chat window.

[![Available](https://img.shields.io/badge/Status-Available_for_contract-0ea5e9?style=for-the-badge)](https://github.com/ysadao)
[![GitHub](https://img.shields.io/badge/GitHub-ysadao-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ysadao)

<sub>TypeScript · React · Node · Solana · FastAPI · Docker</sub>

</div>

---

A client does not hire a list of logos. They hire someone who can own **auth, money, isolation, and delivery** without a six-person backend team.

Every system below is public. Clone it, run it, read the architecture. That is the interview.

## Hire me when you need

| Situation | What you get |
| --- | --- |
| A SaaS that must isolate customers | Org RBAC, JWT + API keys, audit log, tenant-scoped data |
| Money moving more than once | Payment intents, **required** idempotency, HMAC webhooks, ledger |
| A Solana / DeFi product surface | Wallet UX, SPL flows, indexer APIs, portfolio / desk UI |
| Internal AI that ops can actually run | Workflows, queue, webhooks, usage, operator UI |

## Open the work

Six systems. Tests, Docker, and CI in each repo.

| Repo | What a client should notice |
| --- | --- |
| **[modern-saas-platform](https://github.com/ysadao/modern-saas-platform)** | Multi-tenant dashboard — register, orgs, roles, isolated projects, audit trail |
| **[payment-service](https://github.com/ysadao/payment-service)** | Charges you can retry safely — idempotency keys, signed provider webhooks, immutable ledger |
| **[identity-access-service](https://github.com/ysadao/identity-access-service)** | Sessions that behave — access + hashed refresh rotation, permissions matrix, API keys |
| **[solana-dapp](https://github.com/ysadao/solana-dapp)** | Wallet surface — SOL / SPL balances, transfers, a clear demo vs live-cluster boundary |
| **[ai-automation-platform](https://github.com/ysadao/ai-automation-platform)** | Workflow runner — templates, worker, completion webhooks, operator UI (provider-swappable) |
| **[defi-trading-dashboard](https://github.com/ysadao/defi-trading-dashboard)** | Desk UI — portfolio, pools, tape, P&amp;L — the product shape a trader actually looks at |

Also public: [multi-tenant-api](https://github.com/ysadao/multi-tenant-api) · [webhook-engine](https://github.com/ysadao/webhook-engine) · [notification-service](https://github.com/ysadao/notification-service) · [blockchain-indexer](https://github.com/ysadao/blockchain-indexer) · [solana-token-platform](https://github.com/ysadao/solana-token-platform) · [web3-portfolio-tracker](https://github.com/ysadao/web3-portfolio-tracker)

## How I build

- **Trust is a feature.** Auth, validation, tenancy, and idempotency land in v1 — not “later.”
- **Boundaries stay explicit.** Tenant vs tenant. App vs wallet vs contract. Demo vs live cluster.
- **You can run what I send.** Docker Compose, GitHub Actions, and a README that tells you the ports.

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nodejs,postgres,redis,python,docker,githubactions" alt="Core stack" />
</p>

| Layer | What I reach for |
| --- | --- |
| Product | TypeScript, React, Node (Express / Nest), Next.js when the product needs it |
| Data | PostgreSQL as source of truth, Redis when the workload needs a cache or queue |
| Chain | Solana (web3.js / Anchor patterns), EVM (viem / wagmi) with wallet and indexer boundaries |
| AI | FastAPI services, workflow runners, webhooks — model provider behind an interface |
| Delivery | Docker, Compose, GitHub Actions — same artifact from laptop to CI |

## Start

If the work above matches the product you are trying to ship, open a GitHub issue on any repo or message **[ysadao](https://github.com/ysadao)**.

I take **contract / freelance** engagements: greenfield product backends, payment and webhook reliability, Solana surfaces, and internal AI runners.
