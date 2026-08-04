# Department of Education (department-of-education)

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

The U.S. Department of Education (ED) is a federal agency that manages and coordinates federal assistance to education and establishes policy for it. ED's mission is to promote student achievement and preparation for global competitiveness, and to ensure equal access to education. The Department exposes a portfolio of public APIs through api.data.gov, NCES, and the Open Data Platform (ODP) at data.ed.gov for postsecondary outcomes, institutional characteristics, and federal education programs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Public

## Tags

- College Scorecard
- Education
- Federal Government
- Higher Education
- IPEDS
- K-12
- NCES
- Open Data
- Postsecondary

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### College Scorecard API

The College Scorecard API provides programmatic access to postsecondary institution and field-of-study data published by the U.S. Department of Education. The API exposes more than 6,000 schools and over 1,900 data points per institution drawn from IPEDS, the National Student Loan Data System (NSLDS), and U.S. Department of the Treasury sources, including cost, completion, earnings, debt, and demographic outcomes. Requests require an api.data.gov API key passed via the api_key query parameter.

- **Human URL:** [https://collegescorecard.ed.gov/data/](https://collegescorecard.ed.gov/data/)
- **Base URL:** `https://api.data.gov/ed/collegescorecard/v1`

#### Tags

- College Scorecard
- Earnings
- Higher Education
- Postsecondary
- Schools

#### Properties

- [Documentation](https://collegescorecard.ed.gov/data/api-documentation/)
- [A P I](https://collegescorecard.ed.gov/data/api/)
- [Data](https://collegescorecard.ed.gov/data/)
- [Git Hub](https://github.com/RTICWDT/college-scorecard)
- [Sign Up](https://api.data.gov/signup/)
- [Postman Collection](collections/department-of-education.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-education.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Department of Education Open Data Platform API

The Department of Education Open Data Platform (ODP) at data.ed.gov is built on CKAN and exposes a CKAN-compatible REST API for searching, retrieving, and downloading the Department's public datasets. The API surface mirrors CKAN package, resource, group, and search actions over JSON.

- **Human URL:** [https://data.ed.gov/](https://data.ed.gov/)
- **Base URL:** `https://data.ed.gov/api/3`

#### Tags

- CKAN
- Datasets
- Open Data

#### Properties

- [Documentation](https://data.ed.gov/about)
- [F A Q](https://data.ed.gov/faq)
- [User  Guide](https://data.ed.gov/pages/publichelp)
- [C K A N  Reference](https://docs.ckan.org/en/2.8/api/)
- [Postman Collection](collections/department-of-education.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-education.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IPEDS Data

The Integrated Postsecondary Education Data System (IPEDS) gathers data annually from every college, university, and technical and vocational institution that participates in the federal student financial aid programs. NCES distributes IPEDS data via downloadable CSV files, Access databases, and a Find Your College tool rather than a public REST API; many of these datasets are also exposed via the College Scorecard and ODP APIs.

- **Human URL:** [https://nces.ed.gov/ipeds](https://nces.ed.gov/ipeds)
- **Base URL:** `https://api.example.com`

#### Tags

- Bulk Data
- Higher Education
- IPEDS
- NCES
- Postsecondary

#### Properties

- [Documentation](https://nces.ed.gov/ipeds)
- [Use the  Data](https://nces.ed.gov/ipeds/use-the-data)
- [Find  Your  College](https://nces.ed.gov/ipeds/find-your-college)
- [Downloads](https://nces.ed.gov/ipeds/use-the-data/download-access-database)
- [Postman Collection](collections/department-of-education.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-education.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- Bulk Data
- EDFacts
- K-12
- State Data

#### Properties

- [Documentation](https://www2.ed.gov/about/inits/ed/edfacts/index.html)
- [Data  Files](https://www2.ed.gov/about/inits/ed/edfacts/data-files/index.html)
- [Education  Data  Explorer](https://educationdata.urban.org/documentation/)
- [Postman Collection](collections/department-of-education.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-education.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usedgov)
- [Website](https://www.ed.gov)
- [Open  Data  Platform](https://data.ed.gov/)
- [Developer  Portal](https://api.data.gov/)
- [N C E S](https://nces.ed.gov/)
- [College  Scorecard](https://collegescorecard.ed.gov/)
- [Federal  Student  Aid](https://studentaid.gov)
- [Data.gov  E D  Catalog](https://catalog.data.gov/dataset?organization=ed-gov)
- [News](https://www.ed.gov/news)
- [Contact](https://www.ed.gov/about/contact-us)
- [Privacy Policy](https://www.ed.gov/notices/privacy)
- [GitHub Organization](https://github.com/usedgov)
- [JSON-LD](json-ld/department-of-education-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/department-of-education-vocabulary.yml)
- [Capabilities](capabilities/department-of-education-capabilities.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
