# Veterans Affairs (VA) - APIs.json Profile

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
