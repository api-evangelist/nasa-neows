# NASA NeoWs (nasa-neows)

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
