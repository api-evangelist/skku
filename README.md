# Sungkyunkwan University

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

Sungkyunkwan University (SKKU) is a private research university in Seoul and Suwon, South Korea, founded in 1398 and operated since 1996 under the Samsung Foundation of Education. Like almost every university it is a federation of buyers rather than an API producer, and this profile is deliberate about which of that federation's surfaces are actually SKKU's engineering. SKKU operates no central developer portal and no API gateway — api.skku.edu, developer.skku.edu, data.skku.edu and status.skku.edu do not resolve — and publishes no OpenAPI for anything. What it does operate, and what almost no university catalog records, is a SAML 2.0 identity provider at kafe.skku.edu registered in eduGAIN through KAFE, the Korea Access Federation: entityID https://kafe.skku.edu/idp/simplesamlphp, scope skku.edu, supporting the REFEDS Research and Scholarship entity category and asserting the REFEDS Sirtfi assurance profile. That machine-readable metadata document is the strongest programmable surface SKKU runs. Its research information portal at pure.skku.edu looks institutional and is not: it CNAMEs to skku.elsevierpure.com and its OAI-PMH provider self-identifies as "Pure OAI Repository" with adminEmail purehosted@elsevier.com, so the live, conformant OAI-PMH 2.0 endpoint there is recorded as an Elsevier Pure TENANCY — SKKU's data on Elsevier's contract — and no Pure specification is saved in this repository. The thesis repository at skku.dcollection.net is likewise a KERIS dCollection tenancy whose robots.txt disallows all crawling and whose OAI paths return an HTML shell. Two SKKU units are Crossref members in their own right (School of Medicine, prefix 10.23838; Institute of Legal Studies, prefix 10.17008) and the institution is registered in ROR as 04q78tk20; no DataCite provider or client exists. Everything else — Kingo Portal SSO, iCampus, course registration at sugang.skku.edu, the library discovery layer — is enrolment-gated with no public API, no developer registration and no published rate limits.

**Areas:** University · Higher Education · Education · Research · South Korea · Seoul · Identity Federation · SAML · eduGAIN · Research Repository · OAI-PMH · Open Access

## Sungkyunkwan University on APIs.io

Everything profiled for Sungkyunkwan University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/skku/](https://apis.io/providers/skku/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [SKKU SAML 2.0 Identity Provider (KAFE / eduGAIN metadata)](https://apis.io/apis/skku/identity-federation/) — Sungkyunkwan University's institutional identity provider, publishing machine-readable SAML 2.0 metadata through the KAFE (Korea Access Federation)…
- [SKKU Research Portal (Elsevier Pure) — TENANT](https://apis.io/apis/skku/pure-research-portal/) — SKKU's research information system and public researcher/output profiles, running on Elsevier Pure at pure.skku.edu. This is a genuine institutional fact…
- [SKKU dCollection Thesis Repository (KERIS) — TENANT](https://apis.io/apis/skku/dcollection-repository/) — SKKU's electronic theses and dissertations repository, running on dCollection, the national academic-information distribution platform operated for Korean…
- [SKKU Crossref Membership (DOI registration)](https://apis.io/apis/skku/crossref-membership/) — Two Sungkyunkwan University units are Crossref members in their own right and register DOIs under their own prefixes — member 9930, Sungkyunkwan University…
- [SKKU ROR Registration (organization identifier)](https://apis.io/apis/skku/ror-registration/) — Sungkyunkwan University is registered in the Research Organization Registry as https://ror.org/04q78tk20, with registrable domain skku.edu, established…
- [Kingo Portal (campus SSO and gated student systems)](https://apis.io/apis/skku/kingo-portal/) — Kingo Portal is SKKU's single sign-on environment, the front door to the university's own online services — Google Workspace, GLS, iCampus…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Skku Context](https://apis.io/jsonld/skku/skku-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Skku Authentication](https://apis.io/security/skku/skku-authentication/)
- [Skku Domain Security](https://apis.io/security/skku/skku-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Skku Plans Pricing](https://apis.io/plans/skku/skku-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Skku Rate Limits](https://apis.io/rate-limits/skku/skku-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Skku Finops](https://apis.io/finops/skku/skku-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.skku.edu/eng/)
- [Documentation](https://www.skku.edu/eng/CampusLife/ITServices/KingoPortal1_1.do)
- [Support](https://www.skku.edu/eng/CampusLife/ITServices/ITCallCenter.do)
- [Terms of service](https://www.skku.edu/skku/etc/netizen.do)
- [Privacy policy](https://www.skku.edu/skku/etc/private.do)

## API Evangelist rating

**Kin Score 26.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 20.4 |
| Contract governance | 18.2 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 26.3 |

**Agent readiness 4.4** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 32.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/skku/](https://apis.io/providers/skku/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sungkyunkwan University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/skku/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
