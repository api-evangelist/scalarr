# Scalarr

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

Scalarr Inc. is a cybersecurity company that now operates primarily as AI EdgeLabs (edgelabs.ai), an AI-native runtime detection and response platform for workloads, containers, GPU environments, AI agents and edge infrastructure, with local inference, zero data egress, and out-of-the-box NIS2 and Cyber Resilience Act control mapping in its Compliance Center. It publishes Parallax, an Apache-2.0 runtime security engine for AI agents written in Rust, which ships as a single binary exposing a two-endpoint HTTP evaluation API (POST /evaluate, GET /health) plus a proxy mode that sits between an agent and the LLM API, 54 curated rules across five evaluator engines, and first-party integrations for OpenClaw, Claude Code and the Codex CLI. Scalarr's original business - the machine-learning mobile ad-fraud Protection Suite and DeepView on scalarr.io - appears dormant: the site is still served but its content and sitemap have not been updated since 2022-2023 and api.scalarr.io answers every path with a default OpenResty 404. Scalarr is a portfolio company of Speedinvest. The hosted AI EdgeLabs platform API at portal.edgelabs.ai/api/ is real but undocumented and authentication-gated; no OpenAPI, AsyncAPI, GraphQL schema or MCP server is published for any surface.

**Areas:** Company · Cybersecurity · Runtime Security · AI Agent Security · Container Security · Kubernetes · Edge Computing · Vulnerability Management · Compliance · NIS2 · Machine Learning · Artificial Intelligence

## Scalarr on APIs.io

Everything profiled for Scalarr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/scalarr/](https://apis.io/providers/scalarr/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Parallax Evaluation API](https://apis.io/apis/scalarr/parallax-evaluation-api/) — Self-hosted HTTP API of Parallax, the Apache-2.0 runtime security engine Scalarr publishes for AI agents. Two endpoints: POST /evaluate takes a lifecycle…
- [AI EdgeLabs Portal API](https://apis.io/apis/scalarr/ai-edgelabs-portal-api/) — The HTTP API behind the AI EdgeLabs customer console at portal.edgelabs.ai. Confirmed live on 2026-08-13 - every path under /api/ answered HTTP 401 with a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Scalarr Parallax Webhooks](https://apis.io/asyncapis/scalarr/scalarr-parallax-webhooks/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Scalarr Authentication](https://apis.io/security/scalarr/scalarr-authentication/)
- [Scalarr Domain Security](https://apis.io/security/scalarr/scalarr-domain-security/)
- [Scalarr Vulnerability Disclosure](https://apis.io/security/scalarr/scalarr-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Scalarr Plans Pricing](https://apis.io/plans/scalarr/scalarr-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Scalarr Rate Limits](https://apis.io/rate-limits/scalarr/scalarr-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://scalarr.io)
- [Pricing](https://edgelabs.ai/pricing)
- [Sign up](https://portal.edgelabs.ai)
- [Support](https://edgelabs.ai/contact-us)
- [Blog](https://edgelabs.ai/blog)
- [Terms of service](https://scalarr.io/document/services_agreement/)
- [Privacy policy](https://scalarr.io/document/scalarr-privacy-policy/)
- [GitHub](https://github.com/agent-defense)

## API Evangelist rating

**Kin Score 50.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 54.8 |
| Access clarity | 63.2 |

**Agent readiness 21.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 28.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/scalarr/](https://apis.io/providers/scalarr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Scalarr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/scalarr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
