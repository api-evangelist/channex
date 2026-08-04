# Channex (channex)

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
