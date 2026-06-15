# Maxar (maxar)

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
