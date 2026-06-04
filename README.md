# Purdue University (purdue)

Purdue University is a public land-grant research university in West Lafayette, Indiana, United States, ranked #99 in the QS World University Rankings 2025. This repository catalogs Purdue's public, machine-readable developer/API footprint as an [APIs.json](http://apisjson.org) profile. Purdue does not publish a single centralized developer portal; the confirmed public interfaces are the community-built Purdue.io course-catalog API and the PURR research-repository OAI-PMH endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/purdue/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=purdue-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research
- Open Data
- United States

## APIs

- **Purdue.io Course Catalog API** — Community-built public OData/REST API for Purdue's course catalog (Campuses, Buildings, Rooms, Terms, Courses, Subjects, Sections). Base URL: `https://api.purdue.io/odata/`. Docs: https://github.com/Purdue-io/PurdueApi
- **PURR OAI-PMH Metadata API** — Purdue University Research Repository OAI-PMH endpoint for harvesting research dataset metadata (oai_dc / Dublin Core). Base URL: `https://purr.purdue.edu/oaipmh`. Docs: https://purr.purdue.edu/kb/finduse/oaipmh

## Plans

- [plans/purdue-plans-pricing.yml](plans/purdue-plans-pricing.yml)

## Rate Limits

- [rate-limits/purdue-rate-limits.yml](rate-limits/purdue-rate-limits.yml)

## FinOps

- [finops/purdue-finops.yml](finops/purdue-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.purdue.edu/
- GitHub: https://github.com/Purdue
- LinkedIn: https://www.linkedin.com/school/purdue-university/
- Plans: plans/purdue-plans-pricing.yml
- Rate Limits: rate-limits/purdue-rate-limits.yml
- FinOps: finops/purdue-finops.yml
- Review: review.yml

## Notes

- All APIs and endpoints were probed live during cataloging; only verified, publicly observable interfaces are listed. No endpoints were fabricated.
- The Purdue Libraries API host (`https://api.lib.purdue.edu/`) resolves but serves only a placeholder page and is therefore excluded from the cataloged APIs.
- The Purdue.io API is community/student-built rather than an official Purdue IT product, but is publicly available and returned live catalog data.

## Maintainers

- Kin Lane — kin@apievangelist.com
