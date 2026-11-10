# Chord

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Chord is an AI-powered trading desk offering a non-custodial trading API. Users can ask about any token, stock, perpetual contract, or gold, and receive natural‑language answers based on on‑chain swaps, order books, and news. The platform aims to make trading one tap away in a user's wallet, providing market data and execution via a simple API.

**Areas:** Finance · Trading · AI · Crypto · API

## Chord on APIs.io

Everything profiled for Chord is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/getchord-xyz/](https://apis.io/providers/getchord-xyz/)** — or go straight to one of the APIs or properties below.

### APIs (19)

- [Chord Account and health API](https://apis.io/apis/getchord-xyz/getchord-xyz-account-and-health-api/) — Your key, and the service's own health.
- [Chord Agents and status API](https://apis.io/apis/getchord-xyz/getchord-xyz-agents-and-status-api/) — What an agent starts from: the chain directory (which capability lives on which route, per chain), the hosted MCP server, per-chain health, the public…
- [Chord Arc data API](https://apis.io/apis/getchord-xyz/getchord-xyz-arc-data-api/) — Arc (chain 5042): chain totals, every token traded, launches, launchers, holders — from Chord's own rollup and index tables.
- [Chord Ask agent API](https://apis.io/apis/getchord-xyz/getchord-xyz-ask-agent-api/) — The analyst agent over the Arc index, its picks and research notes.
- [Chord Avalanche, Base, BNB Chain API](https://apis.io/apis/getchord-xyz/getchord-xyz-avalanche-base-bnb-chain-api/) — Avalanche C-Chain (43114), Base (8453), BNB Chain (56), Arbitrum One (42161) and Ethereum (1): chain totals, the 24-hour token board, prints, one token's…
- [Chord Backtests API](https://apis.io/apis/getchord-xyz/getchord-xyz-backtests-api/) — Bar-close strategy backtests over Chord's stored candles: any Hyperliquid perp, 13 FX pairs and metals. Simulated, nothing is traded.
- [Chord Bridge API](https://apis.io/apis/getchord-xyz/getchord-xyz-bridge-api/) — Circle CCTP fast transfer to Arc, and LI.FI routes from 60+ chains.
- [Chord Liquidity API](https://apis.io/apis/getchord-xyz/getchord-xyz-liquidity-api/) — Liquidity: events, pools ranked for providers, positions valued live, LP leaderboard, range planning and backtests, alerts.
- [Chord Meta aggregator API](https://apis.io/apis/getchord-xyz/getchord-xyz-meta-aggregator-api/) — One quote and one unsigned transaction on any Chord chain, for agents. Chord's own router answers first; a third-party aggregator (KyberSwap, Monorail,…
- [Chord Points API](https://apis.io/apis/getchord-xyz/getchord-xyz-points-api/) — The Chord points program on Arc.
- [Chord Portfolio API](https://apis.io/apis/getchord-xyz/getchord-xyz-portfolio-api/) — One wallet's holdings and 24h / 7d / 30d PnL on every chain and Solana by one rule, its swaps across chains, and the older per-chain average-cost PnL, trade…
- [Chord Quote and swap API](https://apis.io/apis/getchord-xyz/getchord-xyz-quote-and-swap-api/) — Best-route quotes across every venue on the chain, and the unsigned transaction to execute them.
- [Chord Robinhood Chain data API](https://apis.io/apis/getchord-xyz/getchord-xyz-robinhood-chain-data-api/) — Robinhood Chain (chain 4663): chain totals, tokens and tokenized stocks from the rollup tables.
- [Chord Solana data API](https://apis.io/apis/getchord-xyz/getchord-xyz-solana-data-api/) — Solana, read-only: chain totals, the 24-hour token board, search, one token's stats, prints, candles and traders, the day's trader board, a wallet's PnL,…
- [Chord Solana swaps API](https://apis.io/apis/getchord-xyz/getchord-xyz-solana-swaps-api/) — Solana swaps, open to everyone: every quote builds Chord's own route (Raydium, Orca, Meteora, pump.fun, PumpSwap) and Jupiter's for the wallet, simulates…
- [Chord Streaming API](https://apis.io/apis/getchord-xyz/getchord-xyz-streaming-api/) — Server-sent events and the public WebSocket.
- [Chord Token safety API](https://apis.io/apis/getchord-xyz/getchord-xyz-token-safety-api/) — Chord's safety report for one token on its eight EVM chains or Solana: its own contract scan and buy-then-sell simulation, GoPlus (Powered by Go+ Security),…
- [Chord Tokens and charts API](https://apis.io/apis/getchord-xyz/getchord-xyz-tokens-and-charts-api/) — Curated lists, candles, trade tapes, windowed stats and logos. Address-keyed routes serve both chains.
- [Chord Top wallets API](https://apis.io/apis/getchord-xyz/getchord-xyz-top-wallets-api/) — Wallets ranked from the tape by a skill-adjusted score, with routers and bots removed.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Chord Agentic Access](https://apis.io/agentic-access/getchord-xyz/getchord-xyz-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [LpLeaderRow](https://apis.io/schemas/getchord-xyz/getchord-xyz-lp-leader-row/)
- [MetaQuote](https://apis.io/schemas/getchord-xyz/getchord-xyz-meta-quote/)
- [PoolListRow](https://apis.io/schemas/getchord-xyz/getchord-xyz-pool-list-row/)
- [SolTokenRow](https://apis.io/schemas/getchord-xyz/getchord-xyz-sol-token-row/)
- [SolTradeQuote](https://apis.io/schemas/getchord-xyz/getchord-xyz-sol-trade-quote/)
- [TokenRiskReport](https://apis.io/schemas/getchord-xyz/getchord-xyz-token-risk-report/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Getchord Xyz Context](https://apis.io/jsonld/getchord-xyz/getchord-xyz-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Chord API Rules](https://apis.io/rules/getchord-xyz/getchord-xyz-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Chord Authentication](https://apis.io/security/getchord-xyz/getchord-xyz-authentication/)
- [Chord Domain Security](https://apis.io/security/getchord-xyz/getchord-xyz-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Chord Plans Pricing](https://apis.io/plans/getchord-xyz/getchord-xyz-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Chord Rate Limits](https://apis.io/rate-limits/getchord-xyz/getchord-xyz-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://getchord.xyz/)
- [Documentation](https://getchord.xyz/developer)
- [Getting started](https://getchord.xyz/docs/get-started/)
- [API reference](https://getchord.xyz/developer)
- [Pricing](https://getchord.xyz/pricing)
- [Changelog](https://getchord.xyz/docs/resources/changelog/)
- [Terms of service](https://getchord.xyz/terms)
- [Privacy policy](https://getchord.xyz/privacy)
- [Status](https://getchord.xyz/status)

## API Evangelist rating

**Kin Score 61.8** — strong · rubric 0.27.0 · scored 2026-11-10

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 62.4 |
| Contract governance | 79.1 |
| Operational transparency | 60.0 |
| Developer ergonomics | 46.9 |
| Access clarity | 60.0 |

**Agent readiness 47.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 26.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/getchord-xyz/](https://apis.io/providers/getchord-xyz/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Chord: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/getchord-xyz/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
