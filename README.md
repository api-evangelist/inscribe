# Inscribe (inscribe)

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

Inscribe is an AI-powered document fraud detection platform founded in 2017, serving banks, credit unions, fintechs, and lending institutions. The platform uses agentic AI trained by fraud experts to detect forged, manipulated, and AI-generated documents including bank statements, pay stubs, tax forms, invoices, and identity documents. Inscribe's REST API provides programmatic access to fraud detection, document verification, credit insights, and transaction enrichment workflows at scale. Financial institutions integrate the API to automate underwriting, onboarding, KYC/KYB, and bank account verification decisions, with results delivered via webhook or polling.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/inscribe/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=inscribe-api-evangelist&utm_content=repo

## Tags

Fraud Detection, Document Verification, Financial Services, KYC, KYB, Bank Statements, Pay Stubs, Identity Verification, Risk Management, Fintech, AI, Machine Learning

## APIs

### Inscribe Document Fraud Detection API

RESTful API for uploading and analyzing financial documents for fraud detection and data extraction. Supports bank statements, pay stubs, tax forms, invoices, and identity documents. Provides fraud signals, forensic analysis, and structured data extraction with results delivered via webhook or polling. Includes customer management, bank account analysis, collect sessions, open banking data ingestion, and transaction enrichment endpoints.

- **Base URL:** https://api.inscribe.ai/api/v2
- **API Reference:** https://docs.inscribe.ai/reference/overview
- **OpenAPI / llms.txt:** https://docs.inscribe.ai/llms.txt

**Key Endpoint Groups:**
- Customer Management (create, retrieve, list, update, delete)
- Bank Accounts (retrieve, list, credit analysis)
- Documents (upload, retrieve, list, update, delete) — max 50 MB, 350 pages per PDF
- Collect Sessions (create, retrieve, list, update)
- Open Banking Data (Inscribe Financial Data Format, MX, Plaid Asset Reports)
- Transactions (list, categorize, recategorize)
- Credit Insights (cashflow, income, risk, expenditure, loan summaries)

## Plans / Rate Limits / FinOps

- **Plans:** [plans/inscribe-plans-pricing.yml](plans/inscribe-plans-pricing.yml) — Custom enterprise pricing; median ~$24,500/yr, range $1K–$60K
- **Rate Limits:** [rate-limits/inscribe-rate-limits.yml](rate-limits/inscribe-rate-limits.yml) — Default: 300 req/2 min; Elevated: 3,000 req/5 min (on request)
- **FinOps:** [finops/inscribe-finops.yml](finops/inscribe-finops.yml) — Usage-metered; primary cost driver is documents processed

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.inscribe.ai/ |
| Documentation | https://docs.inscribe.ai/reference/overview |
| GitHub Organization | https://github.com/InscribeAI |
| LinkedIn | https://www.linkedin.com/company/inscribeai/ |
| X (Twitter) | https://twitter.com/inscribeai |
| Blog | https://www.inscribe.ai/blog |
| Status Page | https://status.inscribe.ai/ |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
