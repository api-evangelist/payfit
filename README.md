# PayFit (payfit)

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

PayFit is a cloud-based payroll and HR platform serving small and mid-sized businesses in France, the United Kingdom, Spain, Germany, and Italy with automated payroll, expense management, leave and time tracking, and employee self-service. The platform handles country-specific payroll calculations, tax filings, and social declarations alongside core HR workflows. PayFit exposes two REST APIs: a Customer API authenticated via private API keys for direct company-data access, and a Partner API using OAuth 2.0 for integration developers building marketplace solutions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/payfit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/payfit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Payroll
- Human Resources
- HR Tech
- Europe Payroll
- Time and Attendance
- Employee Management

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### PayFit Partner API

OAuth 2.0 REST API for solution developers building integrations with PayFit. Once enabled by a customer, partners can synchronize collaborators, payroll journals, meal vouchers, and other HR data.

- **Human URL:** [https://developers.payfit.io/](https://developers.payfit.io/)
- **Base URL:** `https://partner-api.payfit.com`

#### Tags

- Partner API
- OAuth
- Payroll
- HR Integration

#### Properties

- [Documentation](https://developers.payfit.io/)
- [Authentication](https://developers.payfit.io/docs/authentication)
- [Webhooks](https://developers.payfit.io/docs/webhooks)
- [Postman Collection](collections/payfit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/payfit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PayFit Customer API

Private REST API for PayFit customers to access their own company data via long-lived private API keys, suitable for in-house scripts and direct integrations.

- **Human URL:** [https://developers.payfit.io/](https://developers.payfit.io/)
- **Base URL:** `https://api.payfit.com`

#### Tags

- Customer API
- API Key
- Payroll
- HR Data

#### Properties

- [Documentation](https://developers.payfit.io/)
- [Postman Collection](collections/payfit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/payfit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/PayFit)
- [LinkedIn](https://www.linkedin.com/company/payfit)
- [Website](https://payfit.com)
- [Documentation](https://developers.payfit.io/)
- [Pricing](https://payfit.com/uk/pricing/)
- [Sign Up](https://app.payfit.com/signup)
- [L L Ms Txt](https://developers.payfit.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
