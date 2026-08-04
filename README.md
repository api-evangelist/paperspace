# Paperspace (paperspace)

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

Paperspace is a GPU cloud platform for AI, ML, and 3D rendering workloads, acquired by DigitalOcean in 2023. The platform combines on-demand GPU/CPU machines (Core), the Gradient ML workflow stack (Notebooks, Datasets, Models, Workflows), and container-as-a-service Deployments under a single team-scoped REST API at api.paperspace.com/v1. Compute is billed per second across H100, A100, A6000, V100, A5000, A4000, and P6000 SKUs, with Bearer-token authentication using team-scoped API keys.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paperspace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paperspace/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- GPU
- Cloud
- AI
- Machine Learning
- Deep Learning
- Compute
- DigitalOcean
- Containers
- Notebooks
- Gradient

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Paperspace Machines API

Programmatically manage Paperspace virtual machines — GPU and CPU compute instances. Covers the machine lifecycle (create, start, stop, restart, delete), machine events, team-member access grants per machine, desktop streaming configuration, and a region-keyed machine-availability lookup.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/machine/](https://docs.digitalocean.com/reference/paperspace/api-reference/machine/)

#### Tags

- Compute
- GPU
- Machines
- Cloud

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/machine/)
- [OpenAPI](openapi/paperspace-machines-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-machines-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-machines-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/paperspace-machine-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/paperspace-machine-structure.json)
- [JSON-LD](json-ld/paperspace-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Paperspace Deployments API

Container-as-a-service deployments that run user-provided images on Paperspace GPU machines with a managed endpoint, autoscaling, rolling updates, runs, metrics, logs, and revision history. Includes the project-scoped deployment listing.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/deployments/](https://docs.digitalocean.com/reference/paperspace/api-reference/deployments/)

#### Tags

- Containers
- Deployments
- GPU
- Inference

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/deployments/)
- [OpenAPI](openapi/paperspace-deployments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-deployments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-deployments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/paperspace-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Paperspace Projects API

Projects are the top-level organizing container in Paperspace. The Projects API covers project lifecycle, activity feeds, collaborator management, project-scoped secrets, tags, and model linkage.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/project/](https://docs.digitalocean.com/reference/paperspace/api-reference/project/)

#### Tags

- Organization
- Projects
- Collaboration
- Secrets

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/project/)
- [OpenAPI](openapi/paperspace-projects-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-projects-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-projects-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Datasets API

Versioned data collections used by Paperspace Gradient notebooks, workflows, and deployments. The Datasets API exposes the dataset lifecycle plus a versioned data revision sub-resource.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/dataset/](https://docs.digitalocean.com/reference/paperspace/api-reference/dataset/)

#### Tags

- Data
- Datasets
- Versioning
- Gradient

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/dataset/)
- [OpenAPI](openapi/paperspace-datasets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-datasets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-datasets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Networking API

Networking primitives for Paperspace — private networks (VPCs) for east-west machine-to-machine traffic and a claim-assign-release lifecycle for public IPv4 addresses.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/private-networks/](https://docs.digitalocean.com/reference/paperspace/api-reference/private-networks/)

#### Tags

- Networking
- VPC
- Private Networks
- Public IP

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/private-networks/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/public-ips/)
- [OpenAPI](openapi/paperspace-networking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-networking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-networking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Storage API

Storage primitives — shared drives attached to a private network, machine snapshots with point-in-time restore, and external storage provider credentials (S3, GCS, Azure Blob) plus a team utilization breakdown.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/shared-drives/](https://docs.digitalocean.com/reference/paperspace/api-reference/shared-drives/)

#### Tags

- Storage
- Shared Drives
- Snapshots
- Object Storage

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/shared-drives/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/snapshots/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/storage/)
- [OpenAPI](openapi/paperspace-storage-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Templates and Startup Scripts API

OS templates, custom user-created machine templates, and startup scripts (with assign/unassign to machines) used to configure freshly provisioned Paperspace machines.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/custom-templates/](https://docs.digitalocean.com/reference/paperspace/api-reference/custom-templates/)

#### Tags

- Templates
- Startup Scripts
- OS Images
- Custom Templates

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/os-templates/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/custom-templates/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/startup-scripts/)
- [OpenAPI](openapi/paperspace-templates-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-templates-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-templates-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Container Registries API

Manage container registry credentials used by Paperspace Deployments to pull private images, including a test-connection endpoint that verifies the configured credentials.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/container-registries/](https://docs.digitalocean.com/reference/paperspace/api-reference/container-registries/)

#### Tags

- Containers
- Registry
- Credentials

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/container-registries/)
- [OpenAPI](openapi/paperspace-container-registries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-container-registries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-container-registries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Models API

Register and manage trained ML models in the Paperspace Gradient model registry. Models can be associated with projects and consumed by Deployments.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/model/](https://docs.digitalocean.com/reference/paperspace/api-reference/model/)

#### Tags

- AI
- ML
- Model Registry
- Gradient

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/model/)
- [OpenAPI](openapi/paperspace-models-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-models-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-models-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paperspace Team and Authentication API

Session lookup (`/auth/session`), team-member roster with admin-status mutation, team-member removal, and the team-scoped secrets surface used to share credentials across projects in a team.

- **Human URL:** [https://docs.digitalocean.com/reference/paperspace/api-reference/authentication/](https://docs.digitalocean.com/reference/paperspace/api-reference/authentication/)

#### Tags

- Identity
- Teams
- Members
- Secrets
- Session

#### Properties

- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/authentication/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/teams/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-keys/)
- [OpenAPI](openapi/paperspace-team-auth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paperspace-team-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paperspace-team-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.paperspace.com)
- [Documentation](https://docs.digitalocean.com/products/paperspace/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-reference/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/api-keys/)
- [Documentation](https://docs.digitalocean.com/reference/paperspace/cli/)
- [Pricing](https://www.paperspace.com/pricing)
- [Sign Up](https://console.paperspace.com/signup)
- [Console](https://console.paperspace.com)
- [Blog](https://blog.paperspace.com)
- [Forum](https://community.paperspace.com)
- [Status Page](https://status.paperspace.com)
- [Terms of Service](https://www.paperspace.com/legal/terms-of-service)
- [Privacy Policy](https://www.paperspace.com/legal/privacy-policy)
- [Support](https://www.paperspace.com/contact-sales)
- [GitHub Organization](https://github.com/Paperspace)
- [C L I](https://github.com/Paperspace/cli)
- [Documentation](https://github.com/Paperspace/CORE-API-Docs)
- [SDK](https://github.com/Paperspace/paperspace-node)
- [SDK](https://github.com/Paperspace/paperspace-go)
- [SDK](https://github.com/Paperspace/paperspace-python)
- [C L I](https://github.com/Paperspace/gradient-cli)
- [Tool](https://github.com/Paperspace/terraform-provider-paperspace)
- [Tool](https://github.com/Paperspace/deploy-action)
- [Tool](https://github.com/Paperspace/ml-in-a-box)
- [Tool](https://github.com/Paperspace/fastai-docker)
- [Code Examples](https://github.com/Paperspace/app-template)
- [Code Examples](https://github.com/Paperspace/stable-diffusion-app)
- [Code Examples](https://github.com/Paperspace/FastAPI-Template-App)
- [Code Examples](https://github.com/Paperspace/FastAPI-Hugging-Face-Template-App)
- [Code Examples](https://github.com/Paperspace/Flask-Template-App)
- [Courses](https://github.com/Paperspace/PyTorch-101-Tutorial-Series)
- [Code Examples](https://github.com/Paperspace/DataAugmentationForObjectDetection)
- [X (Twitter)](https://x.com/HelloPaperspace)
- [LinkedIn](https://www.linkedin.com/company/paperspace)
- [Plans](plans/paperspace-plans-pricing.yml)
- [Rate Limits](rate-limits/paperspace-rate-limits.yml)
- [Fin Ops](finops/paperspace-finops.yml)
- [Vocabulary](vocabulary/paperspace-vocabulary.yml)
- [Spectral Rules](rules/paperspace-rules.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
