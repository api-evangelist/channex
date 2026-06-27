# Channex (channex)

Channex is a white-label hotel channel manager API that gives Property Management Systems and booking engines a single JSON-based REST integration to distribute availability, rates, and restrictions (ARI) to Booking.com, Airbnb, Expedia, and 50+ other OTAs, and to receive bookings back in real time via webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/channex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/channex/refs/heads/main/apis.yml)

## Tags

- Hospitality
- Channel Manager
- Hotel Distribution
- OTA
- Bookings

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Channex Properties API

Create, read, update, and delete properties (hotels, apartments, vacation rentals) including location, currency, content, photos, facilities, and settings.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/hotels-collection](https://docs.channex.io/api-v.1-documentation/hotels-collection)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Properties
- Hotels
- Inventory

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/hotels-collection)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Room Types API

Manage room types under a property, including counts of rooms, occupancy (adults, children, infants), default occupancy, room kind (room or dorm), and content.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/room-types-collection](https://docs.channex.io/api-v.1-documentation/room-types-collection)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Room Types
- Inventory

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/room-types-collection)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Rate Plans API

Manage pricing plans for room types - sell mode (per room / per person), rate mode (manual, derived, auto, cascade), occupancy price options, meal types, and stay restrictions.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/rate-plans-collection](https://docs.channex.io/api-v.1-documentation/rate-plans-collection)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Rate Plans
- Pricing

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/rate-plans-collection)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Availability and Restrictions (ARI) API

Read and push Availability, Rates, and Inventory (ARI) - update room-type availability and rate-plan rates and restrictions (min/max stay, stop sell, closed to arrival/departure) by date or date range.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/ari](https://docs.channex.io/api-v.1-documentation/ari)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- ARI
- Availability
- Restrictions

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/ari)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Bookings API

Retrieve bookings and booking revisions, consume the revisions feed for PMS sync, acknowledge revisions, and report no-show or invalid-card outcomes.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/bookings-collection](https://docs.channex.io/api-v.1-documentation/bookings-collection)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Bookings
- Reservations

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/bookings-collection)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Channels API

List, add, configure, and remove distribution channels (OTA connections such as Booking.com, Airbnb, and Expedia) including channel settings and room/rate mappings. Available to white-label accounts.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/channel-api](https://docs.channex.io/api-v.1-documentation/channel-api)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Channels
- OTA
- Distribution

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/channel-api)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Channex Webhooks API

Register callback URLs to receive real-time event notifications (ari, booking, message, sync_error, channel, and review events) filtered by event mask and property, with custom headers and a test endpoint.

- **Human URL:** [https://docs.channex.io/api-v.1-documentation/webhook-collection](https://docs.channex.io/api-v.1-documentation/webhook-collection)
- **Base URL:** `https://secure.channex.io/api/v1`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://docs.channex.io/api-v.1-documentation/webhook-collection)
- [OpenAPI](openapi/channex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/channex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/channex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ChannexIO)
- [LinkedIn](https://www.linkedin.com/company/channex-io)
- [Website](https://channex.io/)
- [Documentation](https://docs.channex.io/)
- [Plans](plans/channex-plans-pricing.yml)
- [Rate Limits](rate-limits/channex-rate-limits.yml)
- [Fin Ops](finops/channex-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
