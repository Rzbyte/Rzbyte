# Rizzz

I build safety and intelligence infrastructure for autonomous agents operating in Web3.

Most of my recent work sits at the boundary where autonomous agents touch real money: transaction firewalls that intercept before a wallet signs, policy engines that return deterministic verdicts instead of model guesses, agents that validate their own strategies against live market evidence before capital moves.

---

## Featured Work

### [SafeHands](https://github.com/Rzbyte/safehands-pharos) â€” Transaction firewall for AI agent finance
A deterministic policy engine that issues `ALLOW / REQUIRE_CONFIRMATION / BLOCK` verdicts *before* a wallet signs. Ships as an MCP server, HTTP API, CLI, and npm package. Live on Pharos Pacific Mainnet. No custody, no blind signing.

`TypeScript` Â· `MCP` Â· `A2A` Â· `x402` Â· `Pharos` Â· [safehands.fun](https://safehands.fun) Â· [npm](https://www.npmjs.com/package/safehands-pharos)

---

### [Rivo](https://github.com/Rzbyte/Rivo) â€” Event intelligence and agent validation for DreamDEX
Turns DreamDEX Event Contract probabilities into measurable intelligence. Calibration measured against 2,179 settled contracts (Brier 0.1821). Agents validated economically, not by accuracy. Includes live shadow testing, on-chain testnet execution with transaction proof, and 15 published SDK findings â€” two of which were retracted in public because the measurement was ours, not the venue's.

`TypeScript` Â· `DreamDEX` Â· `Somnia` Â· `Kelly criterion` Â· [x-rivo.vercel.app](https://x-rivo.vercel.app/)

---

### [FSignal](https://github.com/Rzbyte/FSignal) â€” Ghost signal monitor for YC and a16z Speedrun
Persistent Slack monitor that finds founders before the official directory lists them, and proves every early alert with a timestamped receipt from the directory itself. Measured: median lead time 4.4 days, longest 50 days. Precision â‰¥ 90% enforced in CI against 139 real captures.

`Python` Â· `FastAPI` Â· `Algolia` Â· [Live dashboard](https://fsignal-production.up.railway.app)

---

### [PhylaX](https://github.com/Rzbyte/PhylaX) â€” AI execution firewall for OKX X Layer
Scans both tokens for honeypot and rug risk, fetches optimal routes across 500+ DEX paths, builds unsigned transactions â€” server never broadcasts. Dual-LLM provider abstraction with automatic fallback. Approval replay prevention via Redis.

`TypeScript` Â· `OKX Onchain OS` Â· `X Layer` Â· `Claude / DeepSeek`

---

### [CollabOS](https://github.com/Rzbyte/CollabOS) â€” Autonomous creator partnership director
Built on Minds by Animoca Brands. Runs the full partnership lifecycle: finds aligned collaborators, admits them to a trusted Circle, coordinates campaigns, follows up autonomously. 232 tests, Playwright E2E, verified end-to-end against the live Minds platform with zero fixtures.

`TypeScript` Â· `Next.js` Â· `Postgres` Â· `Prisma` Â· `Minds SDK`

---

### [TraceVault](https://github.com/Rzbyte/tracevault) â€” Vector search for incident history
Paste an error. Find the last time something broke like this â€” and what fixed it. Local embeddings (`all-MiniLM-L6-v2`), HNSW cosine search via Actian VectorAI DB. Runs fully offline once the model is cached.

`Python` Â· `FastAPI` Â· `Next.js` Â· `Actian VectorAI` Â· `sentence-transformers`

---

## Stack

```
Languages   TypeScript  Python  Solidity  SQL
Runtimes    Node.js  FastAPI  Docker
Protocols   MCP  A2A  x402  ERC-20  ERC-721  Aave V3
Chains      Pharos  OKX X Layer  Celo  Somnia  Lisk Sepolia  Starknet
Tools       Prisma  Redis  Vercel  Railway  Algolia  viem  ethers
```

---

## Other Projects

| Project | What it is |
|---|---|
| [Piggy_Sentinel](https://github.com/Rzbyte/Piggy_Sentinel) | Autonomous savings agent on Celo â€” goal-driven Aave yield management, non-custodial |
| [vehicle-booking](https://github.com/Rzbyte/vehicle-booking) | Fleet booking system with 2-level approval workflow, usage charts, and Excel export â€” built for a nickel mining company |
| [cellgrade-arkiv-ideathon](https://github.com/Rzbyte/cellgrade-arkiv-ideathon) | AI-powered grading system for student lab work â€” Arkav Ideathon submission |
| [safehands-solana](https://github.com/Rzbyte/safehands-solana) | SafeHands port â€” transaction safety layer for Solana |

---

*Most things here were built under time pressure for a specific problem. The READMEs say what works and what doesn't.*