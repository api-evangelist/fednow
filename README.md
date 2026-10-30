# FedNow Service

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

The FedNow Service is an instant payments rail operated by the Federal Reserve Banks, launched in July 2023 to move funds between U.S. financial institutions in real time, 24 hours a day, 365 days a year, with immediate interbank settlement in central bank money. It is ISO 20022 native and is one of three domestic U.S. rails alongside The Clearing House's RTP network and the ACH network. FedNow is a scheme operator, not a consumer-facing PSP; participating banks and credit unions connect over FedLine (Direct or Advantage), exchange ISO 20022 messages for customer credit transfers, requests for payment, liquidity transfers and system/account reporting, and may optionally use a small set of FedNow REST APIs (Account Balance, Network Intelligence, Participant List, Ping) exposed through the credential-gated FedLine Developer portal. Its public developer surface is documentation- and rulebook-first: ISO 20022 message specifications live behind SWIFT MyStandards and API access is restricted to enrolled institutions, so there is no open, self-serve public API.

**Areas:** Payments · United States · Real-Time Payments · Instant Payments · ISO 20022 · Account-to-Account · Scheme Operator · Federal Reserve

## FedNow Service on APIs.io

Everything profiled for FedNow Service is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fednow/](https://apis.io/providers/fednow/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [FedNow Account Balance API](https://apis.io/apis/fednow/fednow-account-balance-api/) — Account Management API letting a participating financial institution programmatically retrieve its FedNow master account balance information. Documented on…
- [FedNow Network Intelligence API](https://apis.io/apis/fednow/fednow-network-intelligence-api/) — Risk Mitigation API providing fraud-prevention and risk signals across the FedNow network to participating institutions. Documented on the FedLine Developer…
- [FedNow Participant List API](https://apis.io/apis/fednow/fednow-participant-list-api/) — Service Management API returning the current list of FedNow Service participants so an institution can confirm reachable routing endpoints before sending a…
- [FedNow Ping API](https://apis.io/apis/fednow/fednow-ping-api/) — Service Management API used to verify connectivity and availability of the FedNow Service from a participant's connection. Documented on the FedLine…
- [FedNow ISO 20022 Message Specifications](https://apis.io/apis/fednow/fednow-iso-20022-message-specifications/) — The core scheme messaging surface of the FedNow Service. FedNow is ISO 20022 native and defines message types for customer credit transfers, requests for…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fednow Authentication](https://apis.io/security/fednow/fednow-authentication/)
- [Fednow Domain Security](https://apis.io/security/fednow/fednow-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.frbservices.org/financial-services/fednow)
- [Documentation](https://www.frbservices.org/resources/financial-services/fednow)
- [Getting started](https://www.frbservices.org/fedline-solutions/fedline-developer/sign-up)
- [API reference](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)
- [Pricing](https://www.frbservices.org/resources/fees/fednow-2026)
- [Sign up](https://www.frbservices.org/forms/fednow-service)
- [Support](https://www.frbservices.org/contact)
- [Blog](https://www.frbservices.org/news/fed360)
- [Terms of service](https://frbservices.org/terms)
- [Privacy policy](https://app.frbservices.org/terms/privacy.html)
- [Status](https://www.frbservices.org/app/status/serviceStatus.do)

## API Evangelist rating

**Kin Score 36.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 64.3 |
| Access clarity | 44.7 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 29.5** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fednow/](https://apis.io/providers/fednow/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for FedNow Service: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fednow/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
