# Amazon Glue DataBrew (amazon-glue-databrew)

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

AWS Glue DataBrew is a visual data preparation tool that makes it easy for data analysts and data scientists to clean and normalize data to prepare it for analytics and machine learning. It provides over 250 pre-built transformations to automate data preparation tasks.

**URL:** [https://aws.amazon.com/glue/features/databrew/](https://aws.amazon.com/glue/features/databrew/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Data Analytics, Data Preparation, ETL, Machine Learning

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Glue DataBrew API
The AWS Glue DataBrew API provides programmatic access to create and manage datasets, recipes, projects, jobs, and rulesets for visual data preparation and transformation workflows.

**Human URL:** [https://aws.amazon.com/glue/features/databrew/](https://aws.amazon.com/glue/features/databrew/)

#### Tags:

 - Data Analytics, Data Preparation, ETL

#### Properties

- [Documentation](https://docs.aws.amazon.com/databrew/latest/dg/API_Reference.html)
- [OpenAPI](openapi/amazon-glue-databrew-openapi.yaml)
- [GettingStarted](https://aws.amazon.com/glue/features/databrew/)
- [Pricing](https://aws.amazon.com/glue/pricing/)
- [FAQ](https://aws.amazon.com/glue/faqs/)
- [APIReference](https://docs.aws.amazon.com/databrew/latest/dg/API_Reference.html)
- [Authentication](https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html)
- [JSONSchema](json-schema/glue-databrew-dataset-schema.json)
- [JSONLD](json-ld/amazon-glue-databrew-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/glue/features/databrew/)
- [Documentation](https://docs.aws.amazon.com/databrew/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/big-data/tag/aws-glue-databrew/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/databrew/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| 250+ Pre-Built Transformations | Apply over 250 ready-to-use transformations without writing code. |
| Visual Data Preparation Interface | Interactive visual interface to explore and transform data without code. |
| Recipe-Based Transformations | Save transformation steps as reusable, versioned recipes. |
| Data Profiling | Automatically profile datasets to understand quality and distribution. |
| Data Quality Rules | Define and enforce data quality rules with rulesets. |
| Collaborative Projects | Create shared projects for team-based data preparation. |

## Use Cases

| Name | Description |
|------|-------------|
| Analytics Data Preparation | Clean, normalize, and transform raw data for business analytics. |
| Machine Learning Feature Engineering | Prepare features from raw data for training ML models. |
| Data Quality Validation | Profile datasets and apply quality rules before processing. |
| ETL Pipeline Automation | Automate recurring data transformation jobs in pipelines. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Read input datasets from and write transformed output to S3 buckets. |
| AWS Glue Data Catalog | Connect to Glue Data Catalog tables as data sources. |
| Amazon Redshift | Connect to Redshift databases as data sources. |
| Amazon RDS | Use RDS databases as input sources for DataBrew transformation. |
| AWS Lake Formation | Integrate with Lake Formation for secure data lake access. |

## Artifacts

### OpenAPI

- [Amazon Glue DataBrew OpenAPI](openapi/amazon-glue-databrew-openapi.yaml)

### JSON Schema

273 schema files in [json-schema/](json-schema/)

### JSON Structure

273 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon Glue DataBrew Context](json-ld/amazon-glue-databrew-context.jsonld)

### Examples

273 example files in [examples/](examples/)

## Capabilities

### Shared Per-API Definitions

- [Amazon Glue DataBrew](capabilities/shared/amazon-glue-databrew.yaml) — 12 operations for data preparation management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Glue DataBrew Data Preparation](capabilities/amazon-glue-databrew-data-preparation.yaml) | Amazon Glue DataBrew | 12 | Data Analyst, Data Scientist |

## Vocabulary

- [Amazon Glue DataBrew Vocabulary](vocabulary/amazon-glue-databrew-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 7 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Glue DataBrew Spectral Rules](rules/amazon-glue-databrew-spectral-rules.yml) — 7 rules enforcing Amazon Glue DataBrew API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
