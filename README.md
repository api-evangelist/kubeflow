# Kubeflow (kubeflow)

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

Kubeflow is an open-source machine learning platform for Kubernetes, designed to make deployments of ML workflows on Kubernetes simple, portable, and scalable. It provides tools for training, serving, tuning, and managing ML models across the full lifecycle.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kubeflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kubeflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Deep Learning
- Kubernetes
- Machine Learning
- MLOps
- Model Serving
- Model Training
- Open Source

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Kubeflow Pipelines API

REST API for creating, managing, and executing machine learning pipelines on Kubernetes, including experiments, runs, and artifacts.

- **Human URL:** [https://www.kubeflow.org/docs/components/pipelines/](https://www.kubeflow.org/docs/components/pipelines/)
- **Base URL:** `https://your-kubeflow-instance/pipeline`

#### Tags

- Machine Learning
- MLOps
- Pipelines
- Workflows

#### Properties

- [Documentation](https://www.kubeflow.org/docs/components/pipelines/v2/reference/api/kubeflow-pipeline-api-spec/)
- [OpenAPI](https://raw.githubusercontent.com/kubeflow/pipelines/master/backend/api/v2beta1/swagger/pipeline.swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/kubeflow/pipelines)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubeflow Metadata API

API for tracking and managing metadata, artifacts, and lineage for ML workflows running on Kubeflow.

- **Human URL:** [https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/](https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/)

#### Tags

- Artifacts
- Metadata
- ML Tracking

#### Properties

- [Documentation](https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/)
- [GitHub Repository](https://github.com/google/ml-metadata)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KServe Inference API

KServe (formerly KFServing) provides a serverless model inference API on Kubernetes, supporting standardized prediction protocols, autoscaling, and multi-framework model serving.

- **Human URL:** [https://kserve.github.io/website/](https://kserve.github.io/website/)

#### Tags

- Inference
- Model Serving
- Predictions
- Serverless

#### Properties

- [Documentation](https://kserve.github.io/website/modelserving/v1beta1/)
- [OpenAPI](https://raw.githubusercontent.com/kserve/kserve/master/docs/predict-api/v2/rest_predict_v2.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/kserve/kserve)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Katib API

Katib is the Kubeflow component for hyperparameter tuning, neural architecture search, and AutoML, exposing a Kubernetes-native API for defining and running tuning experiments.

- **Human URL:** [https://www.kubeflow.org/docs/components/katib/](https://www.kubeflow.org/docs/components/katib/)

#### Tags

- AutoML
- Hyperparameter Tuning
- Neural Architecture Search

#### Properties

- [Documentation](https://www.kubeflow.org/docs/components/katib/reference/)
- [GitHub Repository](https://github.com/kubeflow/katib)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubeflow Notebooks API

API for managing Jupyter notebook server instances within a Kubeflow cluster, providing isolated, browser-based development environments.

- **Human URL:** [https://www.kubeflow.org/docs/components/notebooks/](https://www.kubeflow.org/docs/components/notebooks/)

#### Tags

- Development Environment
- Jupyter
- Notebooks

#### Properties

- [Documentation](https://www.kubeflow.org/docs/components/notebooks/)
- [GitHub Repository](https://github.com/kubeflow/kubeflow/tree/master/components/notebook-controller)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubeflow Central Dashboard API

API supporting the Kubeflow central dashboard and UI components, which provide a unified interface to all installed Kubeflow components.

- **Human URL:** [https://www.kubeflow.org/docs/components/central-dash/](https://www.kubeflow.org/docs/components/central-dash/)

#### Tags

- Dashboard
- Management
- UI

#### Properties

- [Documentation](https://www.kubeflow.org/docs/components/central-dash/)
- [GitHub Repository](https://github.com/kubeflow/kubeflow/tree/master/components/centraldashboard)
- [Postman Collection](collections/kubeflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubeflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/kubeflow)
- [Website](https://www.kubeflow.org)
- [Documentation](https://www.kubeflow.org/docs/)
- [Getting Started](https://www.kubeflow.org/docs/started/)
- [Blog](https://blog.kubeflow.org/)
- [Git Hub Org](https://github.com/kubeflow)
- [Community](https://www.kubeflow.org/docs/about/community/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
