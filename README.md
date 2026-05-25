# Paperspace

Paperspace is a GPU cloud platform for AI, machine learning, deep learning, and 3D rendering workloads. The company was [acquired by DigitalOcean in 2023](https://www.digitalocean.com/press/releases/digitalocean-acquires-paperspace) and its product surface is now hosted on DigitalOcean documentation. Paperspace combines on-demand GPU/CPU machines (the Core product), the Gradient ML workflow stack (Notebooks, Datasets, Models, Workflows), and container-as-a-service Deployments behind a single team-scoped REST API at `https://api.paperspace.com/v1`.

This repository profiles Paperspace for the [API Evangelist](https://apievangelist.com) catalog. All artifacts are organised under their respective subfolders per the API Evangelist pipeline convention.

## API surface

The Paperspace REST API (~120+ operations across 20+ resource groups) is profiled here as ten focused OpenAPI specs:

| API | OpenAPI |
|---|---|
| Machines (GPU/CPU machine lifecycle, events, accessors, desktop, availability) | [openapi/paperspace-machines-api-openapi.yml](openapi/paperspace-machines-api-openapi.yml) |
| Deployments (container-as-a-service, runs, metrics, logs, history) | [openapi/paperspace-deployments-api-openapi.yml](openapi/paperspace-deployments-api-openapi.yml) |
| Projects (lifecycle, collaborators, secrets, tags, activity, models) | [openapi/paperspace-projects-api-openapi.yml](openapi/paperspace-projects-api-openapi.yml) |
| Datasets (Gradient versioned datasets) | [openapi/paperspace-datasets-api-openapi.yml](openapi/paperspace-datasets-api-openapi.yml) |
| Networking (private networks, public IPs) | [openapi/paperspace-networking-api-openapi.yml](openapi/paperspace-networking-api-openapi.yml) |
| Storage (shared drives, snapshots, storage providers, utilization) | [openapi/paperspace-storage-api-openapi.yml](openapi/paperspace-storage-api-openapi.yml) |
| Templates and Startup Scripts (OS templates, custom templates, scripts) | [openapi/paperspace-templates-api-openapi.yml](openapi/paperspace-templates-api-openapi.yml) |
| Container Registries (registry credentials, test-connection) | [openapi/paperspace-container-registries-api-openapi.yml](openapi/paperspace-container-registries-api-openapi.yml) |
| Models (Gradient model registry) | [openapi/paperspace-models-api-openapi.yml](openapi/paperspace-models-api-openapi.yml) |
| Team and Authentication (session, team members, team secrets) | [openapi/paperspace-team-auth-api-openapi.yml](openapi/paperspace-team-auth-api-openapi.yml) |

Authentication: all endpoints accept a team-scoped API key via `Authorization: Bearer $API_TOKEN`. API keys are managed from Team Settings in the Paperspace console.

## Catalog entry

The full apis.yml lives at [apis.yml](apis.yml) and is published to:

```
https://raw.githubusercontent.com/api-evangelist/paperspace/refs/heads/main/apis.yml
```

## Artifacts

- `openapi/` — 10 OpenAPI 3.0.3 specs (above)
- `capabilities/` — Per-API Naftiko capabilities plus a `gpu-deployment.yaml` workflow capability
- `json-schema/` — JSON Schema for `Machine` and `Deployment`
- `json-structure/` — JSON Structure for `Machine`
- `json-ld/` — `paperspace-context.jsonld` mapping the Paperspace vocabulary to schema.org
- `vocabulary/` — `paperspace-vocabulary.yml` listing Compute, Containers, Storage, Networking, Templating, Data, Identity terms
- `rules/` — `paperspace-rules.yml` Spectral ruleset enforcing kebab-case paths, camelCase properties, Bearer auth, Title Case tags
- `plans/` — `paperspace-plans-pricing.yml` (API Commons Plans 0.1) for Free / Pro / Growth / Team T1 / Team T2 + GPU SKU rates
- `rate-limits/` — `paperspace-rate-limits.yml` (API Commons Rate Limits 0.1) — concurrency, public-IP quota, storage quota
- `finops/` — `paperspace-finops.yml` aligning compute / storage / networking / containers to the FinOps Framework
- `examples/` — Request/response examples for `createMachine` and `upsertDeployment`

## Provider context

- Headquarters: New York City; distributed team
- Founded: 2014 (Y Combinator)
- Investors: Y Combinator, Initialized Capital, Battery Ventures
- Status: NVIDIA Elite Partner; acquired by DigitalOcean in 2023
- 500,000+ users; ~$36M raised pre-acquisition

## Sources

- Product docs: https://docs.digitalocean.com/products/paperspace/
- API reference: https://docs.digitalocean.com/reference/paperspace/api-reference/
- Pricing: https://www.paperspace.com/pricing
- Console: https://console.paperspace.com
- GitHub org: https://github.com/Paperspace
