# FedNow Service (fednow)

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
