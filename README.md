# Inscribe (inscribe)

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
