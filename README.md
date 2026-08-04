# Pie Insurance (pie-insurance)

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

Pie Insurance is a Washington, DC and Denver-based insurtech founded in May 2017 that makes commercial insurance for small businesses, with workers' compensation as its flagship line. Pie underwrites its own workers' comp through The Pie Insurance Company (NAIC 21857) — the carrier formerly known as Pie Casualty Insurance Company, which Pie acquired as Western Select Insurance Company in 2021 and took full-stack in February 2023 with an A- (Excellent) rating from AM Best. In addition to workers' comp, Pie offers business owners policy (BOP), commercial auto, general liability, professional liability, and errors and omissions through partner carriers. The product is sold both direct-to-business and through a partner network of 4,000+ independent insurance agencies, who quote, bind, and service policies via the Pie agency portal and the Pie Partner API. The Partner API (api.post-prod.pieinsurance.com, REST/JSON, documented with OpenAPI 3.0.4) exposes class-code search, eligibility questions, appetite checks, price indications, full bindable quotes, quote documents, and quote PDF retrieval so agency management systems and partner platforms can embed the Pie workers' comp experience without redirecting users off-platform. Coverage is available in 39 states plus DC; 73% of submissions are auto-decided and average quote time is roughly three minutes. The company has raised approximately $621M across Seed through Series D from investors including Allianz X, SVB Capital, Greycroft, Aspect Ventures, and Elefund. CEO and co-founder is John Swigart. The Pie Partner API is the public developer surface; there is no broader open-source SDK or GitHub organization.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pie-insurance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pie-insurance/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Insurance
- Insurtech
- Workers Compensation
- Small Business
- Commercial Insurance
- Business Owners Policy
- Commercial Auto
- General Liability
- Professional Liability
- Agency Portal
- Partner API
- Quoting
- Binding

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Pie Insurance Partner API

REST/JSON Partner API (OpenAPI 3.0.4) that lets independent agencies and partner platforms quote and bind Pie workers' compensation insurance without leaving their own experience. Endpoints cover class-code search, eligibility questions, appetite (single-class and full-state catalog), price indications, full bindable quotes with create/get/update, quote document upload, and quote PDF retrieval. Base URL https://api.post-prod.pieinsurance.com/api/v1. Credentials are issued by Pie partner onboarding; Swagger UI is published at api.post-prod.pieinsurance.com/api/docs.

- **Human URL:** [https://www.pieinsurance.com/agency/api](https://www.pieinsurance.com/agency/api)
- **Base URL:** `https://api.post-prod.pieinsurance.com/api/v1`

#### Tags

- Insurance
- Workers Compensation
- Quoting
- Binding
- Appetite
- Class Codes
- Eligibility
- Partner API

#### Properties

- [Documentation](https://www.pieinsurance.com/agency/api)
- [Documentation](https://api.post-prod.pieinsurance.com/api/docs/index.html)
- [Swagger](https://api.post-prod.pieinsurance.com/api/docs/v1/swagger.json)
- [OpenAPI](openapi/pie-insurance-partner-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pie-insurance-partner-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pie-insurance-partner-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.pieinsurance.com)
- [Portal](https://www.pieinsurance.com/agency)
- [Documentation](https://www.pieinsurance.com/agency/api)
- [Sign Up](https://www.pieinsurance.com/agency/partner-with-pie)
- [Login](https://partner.pieinsurance.com/)
- [Documentation](https://www.pieinsurance.com/agency/appetite-checker)
- [Documentation](https://www.pieinsurance.com/agency/resources)
- [About](https://www.pieinsurance.com/about)
- [Timeline](https://www.pieinsurance.com/about/timeline)
- [Leadership](https://www.pieinsurance.com/about/leadership)
- [Press](https://www.pieinsurance.com/media)
- [Blog](https://www.pieinsurance.com/blog)
- [Careers](https://www.pieinsurance.com/culture/careers)
- [Contact](https://www.pieinsurance.com/contact)
- [Terms of Service](https://www.pieinsurance.com/legal/terms-of-use)
- [Privacy Policy](https://www.pieinsurance.com/legal/privacy-policy)
- [LinkedIn](https://www.linkedin.com/company/pieinsurance)
- [Twitter](https://twitter.com/pieinsurance)
- [Facebook](https://www.facebook.com/pieinsurance)
- [Products](https://www.pieinsurance.com/coverage/workers-compensation-insurance)
- [Products](https://www.pieinsurance.com/coverage/business-owners-policy)
- [Products](https://www.pieinsurance.com/coverage/commercial-auto-insurance)
- [Products](https://www.pieinsurance.com/coverage/general-liability-insurance)
- [Products](https://www.pieinsurance.com/coverage/professional-liability-insurance)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
