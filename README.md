# World Health Organization (WHO) (who)

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

The World Health Organization (WHO) is the United Nations specialized agency for international public health. WHO provides free public REST APIs giving programmatic access to global health statistics, disease surveillance data, immunization coverage, health indicators by country, and the International Classification of Diseases (ICD). The GHO OData API exposes hundreds of health indicators across all WHO member states with no authentication required, while the ICD API provides structured access to ICD-11 and ICD-10 clinical classifications via OAuth 2 credentials obtained through free registration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/who/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/who/refs/heads/main/apis.yml)

## Tags

- Health
- Global Health
- Disease Surveillance
- Immunization
- Health Statistics
- ICD
- WHO
- United Nations
- Open Data

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### WHO GHO OData API

The Global Health Observatory (GHO) OData API provides a query interface to WHO's global health data and statistics, covering hundreds of health indicators across all WHO member states and regions. No authentication is required. Supports OData filtering, field selection, and is compatible with Power BI.

- **Human URL:** [https://www.who.int/data/gho/info/gho-odata-api](https://www.who.int/data/gho/info/gho-odata-api)
- **Base URL:** `https://ghoapi.azureedge.net/api`

#### Tags

- Global Health Observatory
- Health Indicators
- OData
- Open Data

#### Properties

- [Documentation](https://www.who.int/data/gho/info/gho-odata-api)
- [OpenAPI](https://ghoapi.azureedge.net/api/$metadata) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### WHO ICD API

The ICD API provides HTTP-based REST access to the International Classification of Diseases (ICD-11 and ICD-10), including the ICD-11 Foundation Component and Linearizations. Requires free registration to obtain OAuth 2 client credentials. Supports multilingual responses, JSON-LD, and Swagger/OpenAPI documentation.

- **Human URL:** [https://icd.who.int/docs/icd-api](https://icd.who.int/docs/icd-api)
- **Base URL:** `https://id.who.int/`

#### Tags

- ICD-11
- ICD-10
- Disease Classification
- Clinical
- OAuth 2

#### Properties

- [Documentation](https://icd.who.int/docs/icd-api/APIDoc-Version2/)
- [OpenAPI](https://id.who.int/swagger/index.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://icdaccessmanagement.who.int/connect/token)

## Common Properties

- [Website](https://www.who.int)
- [Documentation](https://www.who.int/data/gho/info/gho-odata-api)
- [Git Hub Org](https://github.com/WorldHealthOrganization)
- [LinkedIn](https://www.linkedin.com/company/world-health-organization-who-/)
- [Blog](https://www.who.int/news-room)
- [Pricing](https://icd.who.int/docs/icd-api/license/)
- [X (Twitter)](https://x.com/WHO)
- [Plans](plans/who-plans-pricing.yml)
- [Rate Limits](rate-limits/who-rate-limits.yml)
- [Fin Ops](finops/who-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
