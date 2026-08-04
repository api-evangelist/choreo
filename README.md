# Choreo (choreo)

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

WSO2 Choreo is an enterprise-grade Internal Developer Platform (IDP) and application orchestration platform that helps organizations build, deploy, manage, and observe APIs, microservices, integrations, and AI applications across multi-cloud Kubernetes infrastructure (AWS, Azure, GCP, Vultr, or upstream Kubernetes). Choreo combines API management, CI/CD, GitOps, observability, FinOps, and platform engineering into a single AI-guided experience. Developers connect Git repos and deploy instantly, while platform teams use Choreo to enforce security, governance, and compliance with PCI DSS and SOC 2 Type 2 certifications. The platform orchestrates CNCF tools including Kubernetes, Argo CD, Cilium, Envoy, Helm, Prometheus, OpenSearch, Flux, and KEDA, and exposes APIs for API management, developer portal/marketplace consumption, and observability insights.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/choreo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/choreo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Apps
- API Management
- CI/CD
- Cloud Native
- DevOps
- Developer Portal
- FinOps
- IDE
- Internal Developer Platform
- Kubernetes
- Lifecycle
- Observability
- Orchestration
- Platform Engineering
- Pro-Code API Composition
- Unified
- WSO2
- Workflows

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-19

## APIs

### Choreo API Management API

The Choreo API Management API provides programmatic access to manage the full lifecycle of APIs on the WSO2 Choreo platform. It allows API creators to create, publish, version, and manage APIs, manage organizations, projects, components, builds, and deployments.

- **Human URL:** [https://wso2.com/choreo/docs/](https://wso2.com/choreo/docs/)

#### Tags

- API Management
- Builds
- Components
- Deployments
- Lifecycle
- Organizations
- Projects

#### Properties

- [Documentation](https://wso2.com/choreo/docs/)
- [OpenAPI](openapi/choreo-api-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/choreo-api-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/choreo-api-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/choreo-organization.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-project.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-component.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-api.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-build.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-deployment.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-environment.json) — [JSON Schema](https://json-schema.org/specification)

### Choreo Developer Portal API

The Choreo Developer Portal API enables API consumers to discover, evaluate, subscribe to, and consume APIs hosted on the Choreo platform. It provides access to the API marketplace, application management, subscription management, and credential generation for OAuth 2.0 and API key based authentication.

- **Human URL:** [https://devportal.choreo.dev/](https://devportal.choreo.dev/)

#### Tags

- API Keys
- API Marketplace
- Applications
- Developer Portal
- OAuth
- Subscriptions

#### Properties

- [Documentation](https://wso2.com/choreo/docs/consuming-services/manage-subscription/)
- [OpenAPI](openapi/choreo-developer-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/choreo-developer-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/choreo-developer-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/choreo-application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/choreo-subscription.json) — [JSON Schema](https://json-schema.org/specification)

### Choreo Insights API

The Choreo Insights API provides access to observability, monitoring, and analytics data for APIs and components deployed on the Choreo platform. It enables users to programmatically retrieve usage statistics, latency metrics, error analytics, and operational insights.

- **Human URL:** [https://wso2.com/choreo/docs/monitoring-and-insights/work-with-choreo-insights-api/access-the-choreo-insights-api/](https://wso2.com/choreo/docs/monitoring-and-insights/work-with-choreo-insights-api/access-the-choreo-insights-api/)

#### Tags

- Alerts
- Analytics
- Logs
- Metrics
- Monitoring
- Observability

#### Properties

- [Documentation](https://wso2.com/choreo/docs/monitoring-and-insights/work-with-choreo-insights-api/access-the-choreo-insights-api/)
- [OpenAPI](openapi/choreo-insights-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/choreo-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/choreo-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/choreo-advisors)
- [Website](https://wso2.com/choreo/)
- [Developer Portal](https://devportal.choreo.dev/)
- [Console](https://console.choreo.dev/)
- [Documentation](https://wso2.com/choreo/docs/)
- [Login](https://console.choreo.dev/login)
- [Sign Up](https://console.choreo.dev/signup)
- [Pricing](https://wso2.com/choreo/pricing/)
- [Blog](https://medium.com/choreo-tech-blog)
- [Blog R S S](https://medium.com/feed/choreo-tech-blog)
- [Discord](https://discord.com/invite/wso2)
- [Parent Company](https://wso2.com)
- [A W S Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=ec25fa2f-b833-43d8-9d4c-de13ade0eee7)
- [Azure Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/wso2.choreo)
- [G C P Marketplace](https://console.cloud.google.com/marketplace/product/wso2-public/choreo)
- [Terms of Service](https://wso2.com/terms-of-use/)
- [Privacy Policy](https://wso2.com/privacy-policy/)
- [J S O N L D Context](json-ld/choreo-context.jsonld)
- [Spectral Rules](spectral/choreo-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)
- [Use Cases](undefined)
- [Standards](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
