# Sungkyunkwan University (skku)

Sungkyunkwan University (SKKU) is a private research university in Seoul and Suwon, South Korea, with roots dating to 1398, and is ranked #123 in the QS World University Rankings 2025. This repository catalogs SKKU's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/skku/refs/heads/main/apis.yml>
- Naftiko Run: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=skku-api-evangelist&utm_content=repo>

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, South Korea, Seoul

## APIs

As of this review SKKU publishes no public, documented developer API or open-data portal. The one cataloged entry reflects a gated identity system, not an open API:

- **Kingo Portal (SSO / Identity)** — SKKU's single sign-on environment integrating university online services; gated to enrolled members, no public authentication API. Docs: <https://www.skku.edu/eng/CampusLife/ITServices/KingoPortal1_1.do>

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/skku-plans-pricing.yml](plans/skku-plans-pricing.yml)
- Rate Limits: [rate-limits/skku-rate-limits.yml](rate-limits/skku-rate-limits.yml)
- FinOps: [finops/skku-finops.yml](finops/skku-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.skku.edu/eng/>
- GitHub (community org): <https://github.com/GDG-SKKU>
- LinkedIn: <https://www.linkedin.com/company/sungkyunkwan-university>
- Review: [review.yml](review.yml)

## Notes

- No public developer portal, open-data portal, or documented REST API was found during research.
- Identity and access run through the gated Kingo Portal SSO and eduroam federation, available only to enrolled students, faculty, and staff.
- There is no central institutional GitHub organization; public code is published by research labs and student developer communities (e.g. GDG-SKKU), not by a university API program.
- The LinkedIn company URL is the canonical page; it returns 404 to automated bots but resolves in a browser.
- No endpoints, base URLs, or properties were fabricated. Only URLs verified live (or noted as bot-blocked) are recorded.

## Maintainers

- Kin Lane — <kin@apievangelist.com>
