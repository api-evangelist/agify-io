# Agify.io (agify-io)
Agify.io is a simple REST API that predicts the age of a person based on their first name. Using a large dataset of name-age associations, it returns an estimated age along with a count of how many data points were used and the name's country-localized variant when a country code is provided. Supports batch requests for up to 10 names per call. Used for demographics research, content personalization, and marketing segmentation.

**URL:** [https://agify.io/](https://agify.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Age Prediction, Name Analysis, Demographics, REST API

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-04-19

## APIs

### Agify.io Predict Age API
Predict the age of a person based on their first name. Returns an estimated age, data count used for the prediction, and optionally a country-localized estimate.

**Human URL:** [https://agify.io/documentation](https://agify.io/documentation)

#### Tags:

 - Age Prediction, Name, Demographics

#### Properties

- [Documentation](https://agify.io/documentation)
- [Pricing](https://agify.io/#pricing)
- [OpenAPI](openapi/agify-io-openapi.yaml)

## Common Properties

- [Portal](https://agify.io/)
- [Documentation](https://agify.io/documentation)
- [Pricing](https://agify.io/#pricing)
- [JSONSchema - Age Prediction Schema](https://raw.githubusercontent.com/api-evangelist/agify-io/refs/heads/main/json-schema/agify-io-age-prediction-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agify-io/refs/heads/main/json-ld/agify-io-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agify-io/refs/heads/main/vocabulary/agify-io-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Name-Based Age Prediction | Estimates a person's age from their first name using a large statistical dataset of name-age associations. |
| Country Localization | Accepts an optional ISO 3166-1 country code to return country-specific age predictions for the given name. |
| Batch Processing | Supports up to 10 names per API request using array parameter syntax for efficient bulk predictions. |
| Rate Limit Headers | Returns X-Rate-Limit-Limit, X-Rate-Limit-Remaining, and X-Rate-Limit-Reset headers to track API usage and quota. |
| Free Tier | Free access for up to 100 requests per day without an API key, making it easy to evaluate the service. |

## Use Cases

| Name | Description |
|------|-------------|
| Demographics Research | Analyze name datasets to estimate age distributions across a user base for research and analytics. |
| Content Personalization | Tailor content or product recommendations based on estimated age derived from a user's provided first name. |
| Marketing Segmentation | Segment leads and customers by estimated age group for targeted marketing campaigns without requiring date-of-birth collection. |
| Form Pre-Fill Assistance | Provide age-range hints during user registration to improve form completion rates and data accuracy. |

## Integrations

| Name | Description |
|------|-------------|
| Genderize.io | Sibling API that predicts gender based on first name — commonly used alongside Agify for demographic profiling. |
| Nationalize.io | Sibling API that predicts nationality from first name, completing a demographic analysis trifecta with Agify and Genderize. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Agify.io API](openapi/agify-io-openapi.yaml)

### JSON Schema

- [Age Prediction Schema](json-schema/agify-io-age-prediction-schema.json)

### JSON Structure

- [Age Prediction Structure](json-structure/agify-io-age-prediction-structure.json)

### JSON-LD

- [Agify.io Context](json-ld/agify-io-context.jsonld)

## Vocabulary

- [Agify.io Vocabulary](vocabulary/agify-io-vocabulary.yaml) — Taxonomy mapping 1 resource, 1 action, 1 workflow, and 1 persona for age prediction from names

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
