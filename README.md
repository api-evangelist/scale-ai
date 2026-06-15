# Scale AI (scale-ai)

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
