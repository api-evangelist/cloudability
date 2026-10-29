# Cloudability

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

Cloudability (an IBM Apptio product) is a cloud cost management and FinOps platform providing cost visibility, optimization recommendations, anomaly detection, and governance across AWS, Azure, Google Cloud, and other multi-cloud environments. The Cloudability API v3 is REST-oriented with JSON responses, HTTP basic authentication using an API token, cursor-style limit/offset pagination, and operations for reporting, business mappings, rightsizing recommendations, anomalies, vendor credentials, and views.

**Areas:** Cloud Cost Management · Cost Optimization · FinOps · Multi-Cloud · Recommendations · Reporting

## Cloudability on APIs.io

Everything profiled for Cloudability is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudability/](https://apis.io/providers/cloudability/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Cloudability API v3](https://apis.io/apis/cloudability/api-v3/) — The Cloudability v3 API is the modern REST interface for the platform. It exposes resource-oriented endpoints for reporting, dimensions and metrics,…
- [Cloudability API v1 (Legacy)](https://apis.io/apis/cloudability/api-v1/) — The legacy v1 API remains available for older integrations covering cost reporting and dimensions. Apptio recommends migrating to v3 for new integrations.…
- [Cloudability Reporting API](https://apis.io/apis/cloudability/reporting/) — The Reporting endpoints under v3 build cost-and-usage queries against Cloudability's normalized billing dataset. Callers select metrics (unblended cost,…
- [Cloudability Business Mappings API](https://apis.io/apis/cloudability/business-mappings/) — Business Mappings define rule-based dimensions that allocate spend to cost centers, products, environments, or applications. The API lets callers list,…
- [Cloudability Rightsizing Recommendations API](https://apis.io/apis/cloudability/rightsizing/) — The Rightsizing API surfaces machine-learning generated downsizing, modernization and termination recommendations for AWS EC2, RDS, EBS, Azure VMs and…
- [Cloudability Anomaly Detection API](https://apis.io/apis/cloudability/anomalies/) — The Anomalies API exposes detected cost anomalies on dimensions such as service, account, and business mapping. Callers can query open anomalies, retrieve…
- [Cloudability Vendor Credentials API](https://apis.io/apis/cloudability/vendor-credentials/) — The Vendor Credentials API manages connections to AWS payer accounts, Azure billing scopes, GCP billing projects, OCI tenancies and other cloud vendors. It…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [cloudability-mcp.yml](https://apis.io/servers/cloudability/cloudability-mcp-yml/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloudability Context](https://apis.io/jsonld/cloudability/cloudability-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cloudability API Rules](https://apis.io/rules/cloudability/cloudability-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudability Authentication](https://apis.io/security/cloudability/cloudability-authentication/)
- [Cloudability Domain Security](https://apis.io/security/cloudability/cloudability-domain-security/)
- [Cloudability Trust Center](https://apis.io/security/cloudability/cloudability-trust-center/)
- [Cloudability Vulnerability Disclosure](https://apis.io/security/cloudability/cloudability-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudability Plans Pricing](https://apis.io/plans/cloudability/cloudability-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudability Rate Limits](https://apis.io/rate-limits/cloudability/cloudability-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudability Finops](https://apis.io/finops/cloudability/cloudability-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.apptio.com/products/cloudability/)
- [Documentation](https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas)
- [Getting started](https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=api-getting-started-cloudability-v3)
- [API reference](https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=cloudability-api)
- [Sign up](https://frontdoor.apptio.com/login)
- [Support](https://www.ibm.com/support/pages/node/7032143)
- [Blog](https://www.apptio.com/blog/)
- [Terms of service](https://www.ibm.com/terms)
- [Privacy policy](https://www.apptio.com/company/data-privacy/)
- [GitHub](https://github.com/cloudability)
- [Status](https://status.cloudability.com/)

## API Evangelist rating

**Kin Score 47.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 6.7 |
| Contract governance | 31.8 |
| Operational transparency | 57.9 |
| Developer ergonomics | 69.0 |
| Access clarity | 50.0 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudability/](https://apis.io/providers/cloudability/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloudability: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudability/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
