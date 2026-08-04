# Scale AI (scale-ai)

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

Scale AI is the data engine for AI. The company turns raw data into training data by combining ML-powered pre-labeling with multi-tier human review, and ships an extensive REST API and SDKs for managing labeling, evaluation, and generative-AI data pipelines. The product portfolio spans the Scale Data Engine (foundational labeling and review), the GenAI Data Engine (data for foundation-model training and tuning), the Scale GenAI Platform (deployment and orchestration for generative AI), the Automotive Data Engine (LiDAR, sensor fusion, customer dashboards, Nucleus), and Donovan (Scale's defense / public-sector AI product). The REST API lives at api.scale.com/v1, supports live and sandbox modes, and is wrapped by official Python (scaleapi) and JavaScript (scaleapi) SDKs. The company serves enterprise, insurance, healthcare, and U.S. and global public-sector verticals.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scale-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scale-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Engine
- Labeling
- RLHF
- GenAI Platform
- Donovan
- Defense AI
- LiDAR
- Sensor Fusion
- REST API

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Scale REST API

The Scale REST API is the unified programmatic surface for Scale's data engine. It is built on REST principles with resource-oriented URLs, form-encoded request bodies, JSON responses, and standard HTTP status codes. Endpoints cover tasks (create, retrieve, cancel, set metadata, manage tags and unique identifiers), batches (create, finalize, list, prioritize, retrieve status), projects (creation and management), specialized annotation tasks (image and video, sensor fusion, LiDAR, multi-stage tasks), data retrieval and downloads, taxonomy service management, and callbacks for async operations. The API is versioned (v1), supports live and sandbox modes, and operates on one object per request (no bulk updates).

- **Human URL:** [https://api-reference.scale.com](https://api-reference.scale.com)
- **Base URL:** `https://api.scale.com`

#### Tags

- REST API
- Labeling
- Tasks
- Batches

#### Properties

- [Documentation](https://scale.com/docs/)
- [API Reference](https://api-reference.scale.com)
- [Authentication](https://api-reference.scale.com/docs/api-reference/authentication.md)
- [Getting Started](https://api-reference.scale.com/docs/api-reference/introduction-to-scale-api.md)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scale GenAI Data Engine

The GenAI Data Engine is Scale's product surface for generating, curating, and reviewing data used to train and tune generative-AI foundation models, including RLHF, SFT, evaluation, and red-team data.

- **Human URL:** [https://scale.com/docs/](https://scale.com/docs/)
- **Base URL:** `https://api.scale.com`

#### Tags

- GenAI
- RLHF
- SFT
- Foundation Models

#### Properties

- [Documentation](https://scale.com/docs/)
- [API Reference](https://api-reference.scale.com)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scale GenAI Platform

The Scale GenAI Platform is the deployment and orchestration product for generative-AI applications, used by enterprise and public-sector customers to deliver agentic and generative workflows on top of Scale's data engine.

- **Human URL:** [https://scale.com/docs/](https://scale.com/docs/)

#### Tags

- GenAI Platform
- Agentic AI
- Enterprise

#### Properties

- [Documentation](https://scale.com/docs/)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scale Automotive Data Engine

Scale's Automotive Data Engine covers autonomy-grade data needs including LiDAR labeling, sensor fusion, multi-stage annotation, the customer dashboard, data hosting, and Nucleus for dataset management.

- **Human URL:** [https://scale.com/docs/](https://scale.com/docs/)
- **Base URL:** `https://api.scale.com`

#### Tags

- Automotive
- LiDAR
- Sensor Fusion
- Nucleus

#### Properties

- [Documentation](https://scale.com/docs/)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scale Nucleus

Nucleus is Scale's dataset management product for browsing, querying, and curating ML datasets at scale.

- **Human URL:** [https://scale.com/docs/](https://scale.com/docs/)

#### Tags

- Nucleus
- Dataset Management
- ML Ops

#### Properties

- [Documentation](https://scale.com/docs/)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scale Donovan

Donovan is Scale's AI platform for defense and public-sector use cases, delivering decision-support and analytic capabilities to U.S. and allied government customers.

- **Human URL:** [https://scale.com/donovan](https://scale.com/donovan)

#### Tags

- Donovan
- Defense
- Public Sector

#### Properties

- [Documentation](https://scale.com/donovan)
- [Postman Collection](collections/scale-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scale-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://scale.com)
- [Documentation](https://scale.com/docs/)
- [API Reference](https://api-reference.scale.com)
- [Getting Started](https://api-reference.scale.com/docs/api-reference/introduction-to-scale-api.md)
- [Authentication](https://api-reference.scale.com/docs/api-reference/authentication.md)
- [Blog](https://scale.com/blog)
- [Sign Up](https://dashboard.scale.com)
- [Console](https://dashboard.scale.com)
- [Pricing](https://scale.com)
- [SDK](https://pypi.org/project/scaleapi/)
- [SDK](https://www.npmjs.com/package/scaleapi)
- [Support](https://scale.com)
- [LinkedIn](https://www.linkedin.com/company/scaleai)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
