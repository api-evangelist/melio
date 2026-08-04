# Melio

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

Melio is a B2B payments platform for small businesses that provides a REST API for managing bills, vendors, payment methods, scheduling payments, and syncing with accounting software including QuickBooks, Xero, and NetSuite. Founded in 2018, Melio has processed over $100B in payments for 100,000+ business users and paid 2M+ vendors.

Melio enables software companies to embed bill pay, vendor payments, and invoicing directly inside their products with ACH and card payment options. The platform supports ACH transfers, check payments, wire transfers, international payments, and pay-over-time financing.

**Website:** [meliopayments.com](https://meliopayments.com/)

## Links

- **Developer / Partners:** https://meliopayments.com/partners/
- **Pricing:** https://meliopayments.com/pricing/
- **Help Center:** https://help.melio.com/hc/en-us
- **Blog:** https://meliopayments.com/blog/
- **Security:** https://meliopayments.com/security/
- **Terms of Service:** https://meliopayments.com/legal/terms-of-service
- **Privacy Policy:** https://meliopayments.com/legal/privacy-policy
- **LinkedIn:** https://www.linkedin.com/company/meliopayments/
- **X:** https://x.com/MelioPayments
- **GitHub Org:** https://github.com/melio-payments

## APIs

- **Melio Payments API** — REST API for bills, vendors, payment methods, scheduling, and webhooks
  - Base URL: https://api.meliopayments.com
  - Sandbox: https://alpha-api.meliopayments.com/
  - Auth: OAuth
  - API access available on Platinum (enterprise) tier

## Repository Contents

| File | Description |
|------|-------------|
| [apis.yml](apis.yml) | APIs.json 0.19 index |
| [plans/melio-plans-pricing.yml](plans/melio-plans-pricing.yml) | API Commons Plans 0.1 — subscription tiers and transaction fees |
| [rate-limits/melio-rate-limits.yml](rate-limits/melio-rate-limits.yml) | API Commons Rate Limits 0.1 |
| [finops/melio-finops.yml](finops/melio-finops.yml) | FinOps Framework 1.0 FOCUS-aligned cost guidance |

## Maintainers

- Kin Lane (kin@apievangelist.com)
