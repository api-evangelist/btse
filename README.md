# BTSE

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

BTSE is a global cryptocurrency exchange offering spot, perpetual futures, OTC, earn and wallet services. Its developer program at docs.btse.com publishes OpenAPI 3 contracts for the Markets, Spot, Futures, Wallet, Earn and OTC REST APIs, AsyncAPI contracts for its WebSocket streams, a FIX protocol interface, HMAC-SHA384 request signing, and a testnet at testapi.btse.io.

**Areas:** Company · Cryptocurrency · Exchange · Trading · Digital Assets · Futures · WebSocket

## BTSE on APIs.io

Everything profiled for BTSE is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/btse/](https://apis.io/providers/btse/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [BTSE Account API](https://apis.io/apis/btse/btse-account-api/) — Requires API key with Read permission
- [BTSE Earn API](https://apis.io/apis/btse/btse-earn-api/) — Investment product endpoints
- [BTSE Markets API](https://apis.io/apis/btse/btse-markets-api/) — Public market data shared by spot and futures markets
- [BTSE OTC API](https://apis.io/apis/btse/btse-otc-api/) — OTC trading endpoints
- [BTSE Trade API](https://apis.io/apis/btse/btse-trade-api/) — Requires API key with Trading permission
- [BTSE Trade V3 API](https://apis.io/apis/btse/btse-trade-v3-api/) — The Trade V3 API from BTSE — 11 operation(s) for trade v3.
- [BTSE Trade V4 API](https://apis.io/apis/btse/btse-trade-v4-api/) — The Trade V4 API from BTSE — 7 operation(s) for trade v4.
- [BTSE Wallet API](https://apis.io/apis/btse/btse-wallet-api/) — Requires API key with Read or Transfer permission

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (3)

Event-driven and webhook contracts.

- [Futures WebSocket API](https://apis.io/asyncapis/btse/btse-futures-websocket-asyncapi/)
- [OTC WebSocket API](https://apis.io/asyncapis/btse/btse-otc-websocket-asyncapi/)
- [Spot WebSocket API](https://apis.io/asyncapis/btse/btse-spot-websocket-asyncapi/)

#### Event channels (40)

Individual events and webhooks the provider emits.

- [allPositionV4](https://apis.io/channels/btse/allpositionv4/)
- [auth](https://apis.io/channels/btse/auth/)
- [fills](https://apis.io/channels/btse/fills/)
- [fillsV2](https://apis.io/channels/btse/fillsv2/)
- [allPositionV4](https://apis.io/channels/btse/futures-websocket-api-allpositionv4/)
- [auth](https://apis.io/channels/btse/futures-websocket-api-auth/)
- [fillsV2](https://apis.io/channels/btse/futures-websocket-api-fillsv2/)
- [notificationApiV4](https://apis.io/channels/btse/futures-websocket-api-notificationapiv4/)
- [ping](https://apis.io/channels/btse/futures-websocket-api-ping/)
- [positionsV3](https://apis.io/channels/btse/futures-websocket-api-positionsv3/)
- [snapshotL1:{symbol}](https://apis.io/channels/btse/futures-websocket-api-snapshotl1-symbol/)
- [subscription](https://apis.io/channels/btse/futures-websocket-api-subscription/)
- [tradeHistoryApiV3:{symbol}](https://apis.io/channels/btse/futures-websocket-api-tradehistoryapiv3-symbol/)
- [update:{symbol}_{grouping}](https://apis.io/channels/btse/futures-websocket-api-update-symbol-grouping/)
- [notificationApiV3](https://apis.io/channels/btse/notificationapiv3/)
- [notificationApiV4](https://apis.io/channels/btse/notificationapiv4/)
- [auth](https://apis.io/channels/btse/otc-websocket-api-auth/)
- [auth](https://apis.io/channels/btse/otc-websocket-api-auth-2/)
- [quote](https://apis.io/channels/btse/otc-websocket-api-quote/)
- [ping](https://apis.io/channels/btse/ping/)
- [positionsV3](https://apis.io/channels/btse/positionsv3/)
- [quote](https://apis.io/channels/btse/quote/)
- [snapshotL1:{symbol}](https://apis.io/channels/btse/snapshotl1-symbol/)
- [auth](https://apis.io/channels/btse/spot-websocket-api-auth/)
- [auth](https://apis.io/channels/btse/spot-websocket-api-auth-2/)
- …and 15 more published on APIs.io

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [btse-mcp.yml](https://apis.io/servers/btse/btse-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Btse Agentic Access](https://apis.io/agentic-access/btse/btse-agentic-access/)

#### JSON Schema (41)

The data models the API reads and writes.

- [AccountFee](https://apis.io/schemas/btse/btse-account-fee/)
- [AmendOrderRequest](https://apis.io/schemas/btse/btse-amend-order-request/)
- [AmendOrderResp](https://apis.io/schemas/btse/btse-amend-order-resp/)
- [AssetExchangeRateResponse](https://apis.io/schemas/btse/btse-asset-exchange-rate-response/)
- [ClosePositionResp](https://apis.io/schemas/btse/btse-close-position-resp/)
- [Conditional](https://apis.io/schemas/btse/btse-conditional/)
- [ConvertRequest](https://apis.io/schemas/btse/btse-convert-request/)
- [CreateAddressRequest](https://apis.io/schemas/btse/btse-create-address-request/)
- [CreateOrderRequest](https://apis.io/schemas/btse/btse-create-order-request/)
- [DefaultResponse](https://apis.io/schemas/btse/btse-default-response/)
- [DepositInvestmentRequest](https://apis.io/schemas/btse/btse-deposit-investment-request/)
- [ExchangeInfoResponse](https://apis.io/schemas/btse/btse-exchange-info-response/)
- [FundingRateHistoryResponse](https://apis.io/schemas/btse/btse-funding-rate-history-response/)
- [FuturesOrderResponse](https://apis.io/schemas/btse/btse-futures-order-response/)
- [FuturesUserTrade](https://apis.io/schemas/btse/btse-futures-user-trade/)
- [InvestmentHistoryResponse](https://apis.io/schemas/btse/btse-investment-history-response/)
- [InvestmentOrder](https://apis.io/schemas/btse/btse-investment-order/)
- [InvestmentProduct](https://apis.io/schemas/btse/btse-investment-product/)
- [MarketRiskLimitArrayResponse](https://apis.io/schemas/btse/btse-market-risk-limit-array-response/)
- [MarketsResponse](https://apis.io/schemas/btse/btse-markets-response/)
- [OHLCVResponse](https://apis.io/schemas/btse/btse-ohlcvresponse/)
- [OpenOrderResponse](https://apis.io/schemas/btse/btse-open-order-response/)
- [OrderResp](https://apis.io/schemas/btse/btse-order-resp/)
- [OrderResponse](https://apis.io/schemas/btse/btse-order-response/)
- [OTCAcceptQuoteRequest](https://apis.io/schemas/btse/btse-otcaccept-quote-request/)
- …and 16 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Btse Context](https://apis.io/jsonld/btse/btse-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [BTSE API Rules](https://apis.io/rules/btse/btse-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Btse Authentication](https://apis.io/security/btse/btse-authentication/)
- [Btse Domain Security](https://apis.io/security/btse/btse-domain-security/)

#### Rate limits (1)

Published request limits.

- [Btse Rate Limits](https://apis.io/rate-limits/btse/btse-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.btse.com)
- [Documentation](https://docs.btse.com/)
- [Getting started](https://docs.btse.com/quickstart/)
- [API reference](https://docs.btse.com/api-explorer/markets/markets-api/)
- [Sign up](https://www.btse.com/en/register)
- [Support](https://support.btse.com)
- [Changelog](https://docs.btse.com/spot/changelog)
- [Terms of service](https://www.btse.com/en/termsandconditions)
- [Privacy policy](https://www.btse.com/en/privacy)
- [GitHub](https://github.com/btsecom)

## API Evangelist rating

**Kin Score 55.6** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 77.3 |
| Contract governance | 22.0 |
| Operational transparency | 52.6 |
| Developer ergonomics | 61.9 |
| Access clarity | 34.2 |

**Agent readiness 34.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 23.1** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/btse/](https://apis.io/providers/btse/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for BTSE: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/btse/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
