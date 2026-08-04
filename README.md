# OpenCorporates

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

OpenCorporates is the world's largest open database of companies, providing a REST API for searching and retrieving company registration data, officer information, and corporate filings globally across more than 140 jurisdictions.

## API

The OpenCorporates API (v0.4.8) provides programmatic access to company registration data. Authentication is via API token passed as a query parameter (`api_token`).

**Base URL:** `https://api.opencorporates.com/v0.4`

### Key Endpoints

- `GET /companies/search` - Search companies by name
- `GET /companies/:jurisdiction_code/:company_number` - Retrieve company details
- `GET /companies/:jurisdiction_code/:company_number/filings` - Retrieve statutory filings
- `GET /officers/search` - Search officers and directors
- `GET /officers/:id` - Retrieve individual officer details
- `GET /jurisdictions` - List available jurisdictions
- `GET /account_status` - Check API usage and remaining quota

### Authentication

API token via query parameter: `?api_token=YOUR_TOKEN`

Obtain a token at: https://opencorporates.com/api_accounts/new

## Plans

| Plan | Annual Cost | Monthly Calls | Daily Limit |
|------|------------|---------------|------------|
| Free | £0 | 200 | 50 |
| Essentials | £2,250 | 500 | 200 |
| Starter | £6,600 | 2,500 | 500 |
| Basic | £12,000 | 5,000 | 1,000 |
| Enterprise | Custom | Custom | Custom |

Public benefit access is available for qualifying journalists, NGOs, universities, and anti-corruption research organizations.

## Links

- Website: https://opencorporates.com
- API Documentation: https://api.opencorporates.com/documentation/API-Reference
- Pricing: https://opencorporates.com/pricing/
- Status: https://status.opencorporates.com/
- Blog: https://blog.opencorporates.com
- GitHub: https://github.com/openc
- LinkedIn: https://www.linkedin.com/company/opencorporates
- X: https://twitter.com/opencorporates
