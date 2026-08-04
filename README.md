# Cloudability (cloudability)

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

Cloudability (an IBM Apptio product) is a cloud cost management and FinOps platform providing cost visibility, optimization recommendations, anomaly detection, and governance across AWS, Azure, Google Cloud, and other multi-cloud environments. The Cloudability API v3 is REST-oriented with JSON responses, HTTP basic authentication using an API token, cursor-style limit/offset pagination, and operations for reporting, business mappings, rightsizing recommendations, anomalies, vendor credentials, and views.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

Cloud Cost Management, Cost Optimization, FinOps, Multi-Cloud, Recommendations, Reporting

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-23

## APIs

### Cloudability API v3
The modern REST interface for the platform. Resource-oriented endpoints for reporting, dimensions/metrics, business mappings, anomalies, rightsizing, vendor credentials, views, dashboards, and budgets. Authentication uses HTTP basic auth with an API token.

- Base URL: `https://api.cloudability.com/v3`
- [Documentation](https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=api-getting-started-cloudability-v3)

### Cloudability API v1 (Legacy)
The legacy API remains for older integrations. Authentication is via an `api_key` query parameter. Apptio recommends migrating to v3.

- Base URL: `https://app.cloudability.com/api/v1`
- [Documentation](https://community.ibm.com/community/user/discussion/apis-getting-started-with-cloudability-apis)

### Cloudability Reporting API
Build cost-and-usage queries against Cloudability's normalized billing dataset. Select metrics (unblended cost, amortized cost, usage_quantity), dimensions (vendor, account_id, service_name, region, business_mapping), filters and date ranges; export as JSON or CSV.

### Cloudability Business Mappings API
Define rule-based dimensions that allocate spend to cost centers, products, environments, or applications. Manage rule order, statements, and preview allocation results.

### Cloudability Rightsizing Recommendations API
ML-generated downsizing, modernization and termination recommendations for AWS EC2/RDS/EBS, Azure VMs/disks, and Google Compute Engine instances, with estimated savings, confidence, and utilization metrics.

### Cloudability Anomaly Detection API
Detected cost anomalies on dimensions like service, account, and business mapping. Query open anomalies, retrieve baseline/actual deltas, classify and acknowledge them.

### Cloudability Vendor Credentials API
Manage connections to AWS payer accounts, Azure billing scopes, GCP billing projects, OCI tenancies, etc. List, validate, rotate, and onboard.

## Common Properties

- [Website](https://www.apptio.com/products/cloudability/)
- [Portal](https://www.ibm.com/products/cloudability)
- [Documentation](https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas)
- [GitHub](https://github.com/cloudability)
- [Training](https://education.apptio.com/courses/ibm-cloudability-api)
- [JSON-LD](json-ld/cloudability-context.jsonld)
- [Spectral](rules/cloudability-rules.yml)
- [Naftiko Capabilities](capabilities/cloud-cost-finops.yaml)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
