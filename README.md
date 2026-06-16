# World Health Organization (WHO) (who)

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
