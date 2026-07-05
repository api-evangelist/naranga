# Naranga (naranga)

Naranga is a cloud-based franchise management platform for franchisors and multi-location brands. Its product suite covers franchise sales CRM and lead management (emaximation), operations and multi-location support (nCompass), employee and franchisee training (nSpire), field audits and inspections, task and job scheduling, and local / multi-channel marketing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/naranga/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/naranga/refs/heads/main/apis.yml)

## API Access Model (Honest Status)

**Naranga does not publish a documented public or self-serve developer API.** As of this entry:

- No developer portal.
- No published API reference.
- No OpenAPI / Swagger definition.
- No SDKs.
- No documented authentication, sandbox, or self-serve API keys.

Naranga is accessed through its hosted web applications (for example the nCompass supplier and location portals under `*.naranga.com`) via normal interactive login.

Integrations with third-party systems **do** exist and are referenced across Naranga's product pages and third-party reviews - for example Twilio (SMS), RingCentral, Microsoft 365, AssureSign (e-signature), and lead-capture / Zapier-style connectors. However, these are delivered through Naranga's **partner and professional-services onboarding** - a scoped, multi-week implementation per brand - rather than through open, documented, developer-facing endpoints. Any programmatic access is partner-gated and not publicly specified.

Because no sourced, developer-facing specification exists, this repository intentionally contains **no** `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` artifacts. Nothing was modeled or fabricated. This is an honest stub that documents Naranga's closed access model. If Naranga later publishes developer documentation, this entry should be revisited and the APIs enumerated then.

## Pricing

Quote-based / contact-sales. Naranga does not publish transparent, self-serve pricing tiers; implementation and cost are scoped per brand based on the number of franchisees and the complexity of integrations. Third-party aggregators list a free trial and placeholder starting figures, but no reconciled public rate card is available.

## Tags

- Franchise Management
- Franchise Operations
- Lead Management
- CRM
- Training
- Field Audits
- Multi-Location
- SaaS
- No Public API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/naranga-llc)
- [Website](https://naranga.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
