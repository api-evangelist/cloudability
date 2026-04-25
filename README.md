# Cloudability (cloudability)

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
