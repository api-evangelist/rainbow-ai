# Rainbow.AI (rainbow-ai)

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

Rainbow.AI provides hyperlocal precipitation forecasting APIs that deliver minute-by-minute rain and snow predictions at 1 km resolution, helping businesses and developers optimize weather-sensitive operations with accurate nowcast and map tile data globally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Weather
- Precipitation
- Forecasting
- Nowcast
- Radar
- Tiles
- Geospatial

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Rainbow.AI Nowcast API

The Nowcast API delivers hyperlocal precipitation forecasts with minute-by-minute predictions for the next 4 hours at 1 km spatial resolution. It returns precipitation type and intensity for any global coordinate, updated every 10 minutes.

- **Human URL:** [https://doc.rainbow.ai](https://doc.rainbow.ai)
- **Base URL:** `https://api.rainbow.ai/v1`

#### Tags

- Weather
- Nowcast
- Precipitation
- Forecasting

#### Properties

- [Documentation](https://doc.rainbow.ai)
- [OpenAPI](openapi/rainbow-ai-nowcast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rainbow-ai-nowcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rainbow-ai-nowcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/rainbow-ai-nowcast-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rainbow-ai-nowcast-structure.json)
- [Sign Up](https://developer.rainbow.ai/)
- [Pricing](https://www.rainbow.ai/business)

### Rainbow.AI Tiles API

The Tiles API provides global cloud coverage map tiles with high-resolution weather visualization data (256x256 tiles) delivered via XYZ CDN. Supports real-time and forecasted precipitation layers, updated every 10 minutes.

- **Human URL:** [https://doc.rainbow.ai](https://doc.rainbow.ai)
- **Base URL:** `https://api.rainbow.ai/v1`

#### Tags

- Weather
- Tiles
- Mapping
- Visualization
- Geospatial

#### Properties

- [Documentation](https://doc.rainbow.ai)
- [OpenAPI](openapi/rainbow-ai-tiles-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rainbow-ai-tiles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rainbow-ai-tiles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Sign Up](https://developer.rainbow.ai/)
- [Pricing](https://www.rainbow.ai/business)

## Common Properties

- [GitHub Organization](https://github.com/Rainbow-AI)
- [LinkedIn](https://www.linkedin.com/company/rainbowai)
- [Website](https://www.rainbow.ai)
- [Documentation](https://doc.rainbow.ai)
- [Sign Up](https://developer.rainbow.ai/)
- [Pricing](https://www.rainbow.ai/business)
- [Terms of Service](https://developer.rainbow.ai/terms-of-service)
- [Status Page](https://status.rainbow.ai)
- [Spectral Rules](rules/rainbow-ai-rules.yml)
- [JSON-LD](json-ld/rainbow-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/rainbow-ai-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
