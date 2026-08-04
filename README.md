# TimezoneDB (timezonedb)

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

TimezoneDB is a REST API providing timezone information for cities and coordinates worldwide. It supports looking up local time, GMT offset, and daylight saving time (DST) status by timezone name, geographic coordinates (latitude/longitude), city name, or IP address. The service also supports converting times between timezones and listing all 400+ supported timezones across 240+ countries. Responses are available in JSON or XML formats.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/apis.yml)

## Tags

- Timezone
- Time
- Geographic Coordinates
- DST
- UTC Offset
- Time Conversion
- Location

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### TimezoneDB API

REST API for timezone lookups by zone name, geographic coordinates, city name, or IP address. Supports listing all timezones and converting times between timezones. Returns JSON or XML responses with local time, GMT offset, DST status, country, and abbreviation data.

- **Human URL:** [https://timezonedb.com/api](https://timezonedb.com/api)
- **Base URL:** `https://api.timezonedb.com/v2.1`

#### Tags

- Timezone
- Time Conversion
- Geographic Coordinates
- UTC Offset

#### Properties

- [Documentation](https://timezonedb.com/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/json-schema/list-time-zone-response.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/json-schema/get-time-zone-response.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/json-schema/convert-time-zone-response.json) — [JSON Schema](https://json-schema.org/specification)
- [Examples](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/examples/list-time-zone.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/examples/get-time-zone.json)
- [Examples](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/examples/convert-time-zone.json)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/vocabulary/timezonedb-vocabulary.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/json-ld/timezonedb-context.jsonld)

## Common Properties

- [Website](https://timezonedb.com/)
- [Documentation](https://timezonedb.com/api)
- [Pricing](https://timezonedb.com/premium)
- [Register](https://timezonedb.com/register)
- [X (Twitter)](https://twitter.com/timezonedb)
- [Plans](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/plans/timezonedb-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/rate-limits/timezonedb-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/timezonedb/refs/heads/main/finops/timezonedb-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
