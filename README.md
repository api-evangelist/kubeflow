# Kubeflow (kubeflow)

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
