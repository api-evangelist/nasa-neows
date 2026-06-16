# NASA NeoWs (nasa-neows)

NASA Near Earth Object Web Service (NeoWs) REST API for searching and browsing near Earth asteroid information. Users can search for asteroids based on their closest approach date to Earth, look up a specific asteroid by NASA JPL small body (SPK-ID), and browse the overall dataset. Data originates from the NASA JPL Asteroid team and is maintained by the SpaceRocks Team.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nasa-neows/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nasa-neows/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- NASA
- Asteroids
- Near Earth Objects
- Space
- Science
- Open Data
- Planetary Defense

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### NASA NeoWs API

RESTful web service providing near Earth asteroid information from the NASA JPL Asteroid team. Exposes three endpoints: a date-range feed of close approach events (max 7-day window), a per-asteroid lookup by SPK-ID, and a paginated browse of the complete NEO dataset. Each asteroid record includes estimated diameter, hazardous classification, orbital data, relative velocity, and miss distances in multiple units.

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/neo/rest/v1`

#### Tags

- NASA
- Asteroids
- Near Earth Objects
- NeoWs
- JPL

#### Properties

- [Documentation](https://api.nasa.gov/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nasa-neows/refs/heads/main/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://api.nasa.gov/)
- [Documentation](https://api.nasa.gov/)
- [Git Hub Org](https://github.com/nasa)
- [GitHub Repository](https://github.com/nasa/api-docs)
- [Pricing](https://api.nasa.gov/)
- [Status Page](https://status.api.nasa.gov/)
- [Terms of Service](https://www.usa.gov/developer-apis)
- [Sign Up](https://api.nasa.gov/#signUp)
- [Plans](plans/nasa-neows-plans-pricing.yml)
- [Rate Limits](rate-limits/nasa-neows-rate-limits.yml)
- [Fin Ops](finops/nasa-neows-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
