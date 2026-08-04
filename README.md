# FedNow Service (fednow)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The FedNow Service is an instant payments rail operated by the Federal Reserve Banks, launched in July 2023 to move funds between U.S. financial institutions in real time, 24 hours a day, 365 days a year, with immediate interbank settlement in central bank money. It is ISO 20022 native and is one of three domestic U.S. rails alongside The Clearing House's RTP network and the ACH network. FedNow is a scheme operator, not a consumer-facing PSP: participating banks and credit unions connect over FedLine and exchange ISO 20022 messages, optionally using a small set of FedNow REST APIs exposed through the credential-gated FedLine Developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fednow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fednow/refs/heads/main/apis.yml)

## Tags

- Payments
- United States
- Real-Time Payments
- Instant Payments
- ISO 20022
- Account-to-Account
- Scheme Operator
- Federal Reserve

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## API Posture

FedNow's public developer surface is documentation- and rulebook-first. There is no open, self-serve public API and no publicly downloadable OpenAPI/Swagger specification. API access is gated to enrolled financial institutions through the credential-required FedLine Developer portal, and the ISO 20022 message specifications, implementation guide, message flows, and readiness/testing portal are hosted on SWIFT MyStandards behind a SWIFT account. Authentication and connectivity are handled through FedLine (Direct or Advantage), not a public API key or OAuth flow.

## APIs

### FedNow Account Balance API

Account Management API letting a participating financial institution programmatically retrieve its FedNow master account balance information.

- **Human URL:** [https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)

### FedNow Network Intelligence API

Risk Mitigation API providing fraud-prevention and risk signals across the FedNow network to participating institutions.

- **Human URL:** [https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)

### FedNow Participant List API

Service Management API returning the current list of FedNow Service participants so an institution can confirm reachable routing endpoints before sending a payment.

- **Human URL:** [https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)

### FedNow Ping API

Service Management API used to verify connectivity and availability of the FedNow Service from a participant's connection.

- **Human URL:** [https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)

### FedNow ISO 20022 Message Specifications

The core scheme messaging surface of the FedNow Service — message types for customer credit transfers, requests for payment, interbank liquidity transfers, and system/account reporting, hosted on SWIFT MyStandards.

- **Human URL:** [https://www.frbservices.org/financial-services/fednow/what-is-iso-20022-why-does-it-matter](https://www.frbservices.org/financial-services/fednow/what-is-iso-20022-why-does-it-matter)

## Common Properties

- [Website](https://www.frbservices.org/financial-services/fednow)
- [Developer Portal](https://www.frbservices.org/fedline-solutions/fedline-developer)
- [Documentation](https://www.frbservices.org/resources/financial-services/fednow)
- [API Reference](https://www.frbservices.org/fedline-solutions/fedline-developer/fednow-apis)
- [Pricing](https://www.frbservices.org/resources/fees/fednow-2026)
- [Sign Up](https://www.frbservices.org/forms/fednow-service)
- [Support](https://www.frbservices.org/contact)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
