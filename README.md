# Agify.io (agify-io)

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
