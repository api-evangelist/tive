# Tive (tive)

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

Tive is a real-time supply-chain and shipment visibility platform built on cellular IoT trackers. The Tive Public API (v3) lets you programmatically create and track shipments, manage trackers/devices, pull sensor data (location, temperature, humidity, pressure, light, motion, battery), configure alert presets, and subscribe to webhooks for push event delivery.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tive/refs/heads/main/apis.yml)

## Tags

- Supply Chain
- Shipment Visibility
- Logistics
- IoT
- Trackers
- Real Time

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Tive Shipments API

Create, list, retrieve, update, start, and complete multi-leg shipments (Road, Air, Ocean, Rail) and sync them with existing applications.

- **Human URL:** [https://developers.tive.com/docs/create-a-shipment](https://developers.tive.com/docs/create-a-shipment)
- **Base URL:** `https://api.tive.com/public/v3`

#### Tags

- Shipments
- Logistics
- Tracking

#### Properties

- [Documentation](https://developers.tive.com/docs/create-a-shipment)
- [API Reference](https://developers.tive.com/reference/overview)
- [OpenAPI](openapi/tive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tive Trackers / Devices API

List and retrieve Tive trackers (devices) by deviceId (IMEI) or name, including battery, GPS/WiFi state, and measurement/transmission interval settings.

- **Human URL:** [https://developers.tive.com/docs/devices](https://developers.tive.com/docs/devices)
- **Base URL:** `https://api.tive.com/public/v3`

#### Tags

- Devices
- Trackers
- IoT

#### Properties

- [Documentation](https://developers.tive.com/docs/devices)
- [API Reference](https://developers.tive.com/reference/overview)
- [OpenAPI](openapi/tive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tive Sensor Data API

Retrieve a shipment's tracker sensor data - location, temperature, humidity, pressure, light, motion, and battery - optionally narrowed by a UTC start/end range.

- **Human URL:** [https://developers.tive.com/docs/shipment-data](https://developers.tive.com/docs/shipment-data)
- **Base URL:** `https://api.tive.com/public/v3`

#### Tags

- Sensor Data
- Telemetry
- Location

#### Properties

- [Documentation](https://developers.tive.com/docs/shipment-data)
- [API Reference](https://developers.tive.com/reference/overview)
- [OpenAPI](openapi/tive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tive Alerts API

Create, list, retrieve, and update alert presets - configurable triggers (e.g. high temperature, light detection) attached to shipments and trackers.

- **Human URL:** [https://developers.tive.com/docs/alert-presets](https://developers.tive.com/docs/alert-presets)
- **Base URL:** `https://api.tive.com/public/v3`

#### Tags

- Alerts
- Alert Presets
- Monitoring

#### Properties

- [Documentation](https://developers.tive.com/docs/alert-presets)
- [API Reference](https://developers.tive.com/reference/overview)
- [OpenAPI](openapi/tive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tive Webhooks API

Manage account-level webhooks that push device measurement and alert events to an HTTPS endpoint, scoped to all trackers, shipments, or alert presets.

- **Human URL:** [https://developers.tive.com/docs/webhooks](https://developers.tive.com/docs/webhooks)
- **Base URL:** `https://api.tive.com/public/v3`

#### Tags

- Webhooks
- Events
- Push

#### Properties

- [Documentation](https://developers.tive.com/docs/webhooks)
- [Documentation](https://developers.tive.com/docs/creating-webhooks)
- [OpenAPI](openapi/tive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tive-inc-)
- [Website](https://www.tive.com)
- [Documentation](https://developers.tive.com/docs)
- [Plans](plans/tive-plans-pricing.yml)
- [Rate Limits](rate-limits/tive-rate-limits.yml)
- [Fin Ops](finops/tive-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
