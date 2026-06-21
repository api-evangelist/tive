# Tive (tive)

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
