# Veterans Affairs (VA) - APIs.json Profile

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

APIs.json 0.19 provider profile for the US Department of Veterans Affairs Lighthouse API platform.

## Overview

The VA Lighthouse API platform provides a portfolio of public-facing REST APIs enabling developers, healthcare providers, Veterans Service Organizations (VSOs), and accredited representatives to access veteran data and services. APIs cover:

- **Health** - Patient health records via HL7 FHIR R4, health care costs and coverage
- **Benefits** - Benefits intake, reference data, direct deposit management, letter generation
- **Appeals** - Appeals status and decision reviews (Supplemental Claims, HLR, Board Appeals)
- **Facilities** - VA facility locations, services, and hours
- **Forms** - VA forms metadata and downloads
- **Verification** - Veteran service history, status, and disability rating

## Developer Portal

https://developer.va.gov

## APIs Included

| API | Description |
|-----|-------------|
| Benefits Intake | Upload documents for VA Central Mail processing |
| Patient Health (FHIR) | Veteran health records via FHIR R4 |
| Health Care Costs & Coverage (FHIR) | Health expense data via FHIR |
| Appeals Status | Benefits claim appeal status |
| Decision Reviews | Submit and manage benefit appeals |
| VA Facilities | Facility locations and services |
| VA Forms | Official VA form metadata and downloads |
| Veteran Verification | Service history and disability rating |
| Direct Deposit Management | Direct deposit information for benefits |
| VA Letter Generator | Generate official VA letters |
| Benefits Reference Data | Standardized VA reference data |

## Authentication

- **API Key**: HTTP header `apikey` for server-to-server APIs
- **OAuth 2.0**: OpenID Connect authorization code grant for user-context APIs

## Access

All APIs are free. Sandbox access is available immediately upon API key request. Production access requires an additional review and approval process.

- Sandbox: https://sandbox-api.va.gov
- Production: https://api.va.gov

## Status

https://valighthouse.statuspage.io

## Support

- Email: api@va.gov
- Support portal: https://developer.va.gov/support/contact-us

## Maintainer

Kin Lane &lt;kin@apievangelist.com&gt;
