# Pie Insurance (pie-insurance)

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
