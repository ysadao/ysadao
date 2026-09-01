<div align="center">

# Yamashita Sadao

**Senior full-stack engineer · 10+ years**

Product UIs, APIs, data, and delivery — including on-chain and automation when the product needs them.

</div>

---

## About

I have spent **10+ years** shipping full-stack systems: typed product UIs, multi-tenant APIs, and the auth, data, and delivery work that has to hold up after launch. Web3 and AI show up when the product actually needs a chain surface or a workflow runner — not as a second title.

- Prefer **clear module boundaries** over clever abstractions
- Treat **auth, validation, and migrations** as product features
- Keep **local, CI, and production** as close as the Dockerfile allows

## Selected work

Public systems that show how I design the hard parts of a product.

| System | What it demonstrates |
| --- | --- |
| [modern-saas-platform](https://github.com/ysadao/modern-saas-platform) | Multi-tenant dashboard — JWT, org RBAC, isolated projects, audit log |
| [payment-service](https://github.com/ysadao/payment-service) | Payment intents, required idempotency, HMAC webhooks, ledger |
| [identity-access-service](https://github.com/ysadao/identity-access-service) | Sessions, refresh rotation, permissions matrix, API keys |
| [solana-dapp](https://github.com/ysadao/solana-dapp) | Wallet surface for SOL / SPL balances and transfers |
| [ai-automation-platform](https://github.com/ysadao/ai-automation-platform) | Workflow runner — templates, worker, webhooks, operator UI |
| [blockchain-indexer](https://github.com/ysadao/blockchain-indexer) | Backfill and query APIs for wallet and transaction history |

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,react,nextjs,nodejs,nestjs,express,fastapi,graphql,postgres,redis&perline=12" alt="Languages, product, and data" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=prisma,docker,githubactions,aws,linux,nginx,solidity,git&perline=12" alt="Delivery and chain" />
</p>

| Layer | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, SQL, Solidity |
| Product | React, Next.js, Tailwind CSS |
| APIs | Node.js, NestJS, Express, FastAPI, GraphQL, REST |
| Data | PostgreSQL, Redis, Prisma |
| Auth | JWT, OAuth 2.0, RBAC |
| Chain | Solana (web3.js, Anchor), EVM (viem, wagmi) |
| Delivery | Docker, GitHub Actions, AWS, Nginx, Linux |

Day to day: Next.js and NestJS for product, PostgreSQL as source of truth, FastAPI when automation is its own service, Docker and GitHub Actions so the same artifact moves from laptop to CI.
