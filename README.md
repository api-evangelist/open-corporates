# OpenCorporates

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
