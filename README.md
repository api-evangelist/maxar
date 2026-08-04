# Maxar (maxar)

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

Maxar (operating in 2026 as Vantor / Maxar Intelligence) is a high-resolution Earth observation and 3D geospatial provider operating the WorldView Legion, WorldView-3, WorldView-2, and GeoEye-1 constellations. The Maxar Geospatial Platform (MGP), branded as Vantor Hub, is API-first: developers authenticate through the Authentication / Token Service, search the 125+PB Vivid, archive, and change-monitoring catalog through the Discovery API (STAC / GeoJSON), place orders through the Ordering API, stream imagery and basemaps through OGC-compliant WFS / WMS / WMTS services, retrieve 3D surface models, register Areas of Interest with the Monitoring API, and task new collections through the Tasking API (Fastview / Flexview). Raster and Vector Analytics expose NDVI, NDWI, change-monitoring vectors, and custom analysis graphs. An official Python SDK (maxar-platform) wraps the full surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maxar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maxar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Earth Observation
- Satellite Imagery
- High Resolution
- Geospatial
- 3D
- STAC
- OGC
- WorldView
- Tasking
- Vantor
- Basemaps
- Change Monitoring

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Maxar Authentication / Token Service

OAuth2-style token service that mints bearer access tokens (and 180-day default API keys) for use against all Vantor Hub / MGP APIs.

- **Human URL:** [https://developers.maxar.com/docs/authentication/](https://developers.maxar.com/docs/authentication/)
- **Base URL:** `https://api.maxar.com`

#### Tags

- Auth
- OAuth2
- Tokens

#### Properties

- [Documentation](https://developers.maxar.com/docs/authentication/)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Discovery API

Unified catalog search across Archive Imagery, Vivid Basemaps, and Change Monitoring. Supports filtering and sorting and returns STAC and GeoJSON metadata representations of matching items.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/discovery/v1`

#### Tags

- Discovery
- Search
- STAC
- Catalog

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Ordering API

Order placement and management for archive and online imagery with multiple delivery options and processing pipelines. Supports tracking order status to completion and delivery.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/ordering/v1`

#### Tags

- Ordering
- Delivery
- Processing

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Streaming Imagery API

OGC-compliant WFS / WMS / WMTS streaming services for delivering online imagery strips into web mapping clients and GIS workflows.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/streaming/v1`

#### Tags

- Streaming
- OGC
- WMS
- WMTS

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Streaming Basemap API

OGC service delivering Maxar Vivid basemap products and their metadata for cartographic and analytic use.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/streaming/basemaps`

#### Tags

- Basemaps
- Vivid
- OGC

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Streaming 3D API

Streams 3D surface models derived from Maxar's stereo and tri-stereo collections for visualization and 3D analysis.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/streaming/3d`

#### Tags

- 3D
- Surface Model
- Streaming

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Monitoring API

Register Areas of Interest and receive alerts when new imagery or analytic outputs match. Drives standing tip-and-cue workflows over the Maxar catalog.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/monitoring/v1`

#### Tags

- Monitoring
- Alerts
- AOI

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Tasking API

Request new imagery collection from the WorldView Legion and legacy WorldView constellations within a target geometry and time window. Supports Fastview and Flexview tasking tiers.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/tasking/v1`

#### Tags

- Tasking
- WorldView
- Collection

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Raster Analytics API

Server-side raster processing - band manipulation, classification, and index models (NDVI, NDWI, etc.) - composed as analysis graphs over the Maxar catalog.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/analytics`

#### Tags

- Analytics
- Raster
- NDVI
- NDWI

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Vector Analytics API

Vector deliveries of change monitoring outputs through OGC WMS / WMTS for downstream analytic and GIS consumption.

- **Human URL:** [https://developers.maxar.com/docs](https://developers.maxar.com/docs)
- **Base URL:** `https://api.maxar.com/analytics`

#### Tags

- Vector
- Change Monitoring
- OGC

#### Properties

- [Documentation](https://developers.maxar.com/docs)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar Geospatial Platform Python SDK

Official Python SDK (maxar-platform on PyPI) wrapping the MGP / Vantor Hub APIs for discovery, ordering, monitoring, streaming, and tasking workflows.

- **Human URL:** [https://pypi.org/project/maxar-platform/](https://pypi.org/project/maxar-platform/)
- **Base URL:** `https://pypi.org/project/maxar-platform/`

#### Tags

- SDK
- Python
- PyPI

#### Properties

- [Documentation](https://maxar-geospatial-platform.readthedocs.io/)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maxar MGP Postman Collection

Public Postman workspace documenting the Maxar Geospatial Platform API surface for quick exploration and testing.

- **Human URL:** [https://api-postman.maxar.com/](https://api-postman.maxar.com/)
- **Base URL:** `https://api-postman.maxar.com/`

#### Tags

- Postman
- Collection
- Reference

#### Properties

- [Documentation](https://api-postman.maxar.com/)
- [Postman Collection](collections/maxar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maxar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.maxar.com/)
- [Geospatial Platform](https://maxar.com/maxar-geospatial-platform)
- [Developer Portal](https://developers.maxar.com/)
- [Documentation](https://developers.maxar.com/docs)
- [Authentication](https://developers.maxar.com/docs/authentication/)
- [Release Notes](https://developers.maxar.com/docs/release-notes)
- [Python S D K](https://pypi.org/project/maxar-platform/)
- [S D K Documentation](https://maxar-geospatial-platform.readthedocs.io/)
- [Postman](https://api-postman.maxar.com/) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Pro Docs](https://pro-docs.maxar.com/)
- [LinkedIn](https://www.linkedin.com/company/maxar-technologies/)
- [X (Twitter)](https://x.com/Maxar)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
