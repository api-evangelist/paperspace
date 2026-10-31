# Paperspace

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** GPU · Cloud · Artificial Intelligence · Machine Learning · Deep Learning · Compute · DigitalOcean · Containers · Notebooks · Gradient

## Paperspace on APIs.io

Everything profiled for Paperspace is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/paperspace/](https://apis.io/providers/paperspace/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [Paperspace Machines API](https://apis.io/apis/paperspace/paperspace-machines-api/) — Programmatically manage Paperspace virtual machines — GPU and CPU compute instances. Covers the machine lifecycle (create, start, stop, restart, delete),…
- [Paperspace Deployments API](https://apis.io/apis/paperspace/paperspace-deployments-api/) — Container-as-a-service deployments that run user-provided images on Paperspace GPU machines with a managed endpoint, autoscaling, rolling updates, runs,…
- [Paperspace Projects API](https://apis.io/apis/paperspace/paperspace-projects-api/) — Projects are the top-level organizing container in Paperspace. The Projects API covers project lifecycle, activity feeds, collaborator management,…
- [Paperspace Datasets API](https://apis.io/apis/paperspace/paperspace-datasets-api/) — Versioned data collections used by Paperspace Gradient notebooks, workflows, and deployments. The Datasets API exposes the dataset lifecycle plus a…
- [Paperspace Container Registries API](https://apis.io/apis/paperspace/paperspace-container-registries-api/) — Manage container registry credentials used by Paperspace Deployments to pull private images, including a test-connection endpoint that verifies the…
- [Paperspace Models API](https://apis.io/apis/paperspace/paperspace-models-api/) — Register and manage trained ML models in the Paperspace Gradient model registry. Models can be associated with projects and consumed by Deployments.
- [Paperspace Activity API](https://apis.io/apis/paperspace/paperspace-activity-api/) — The Activity API from Paperspace — 1 operation(s) for activity.
- [Paperspace Authentication API](https://apis.io/apis/paperspace/paperspace-authentication-api/) — The Authentication API from Paperspace — 1 operation(s) for authentication.
- [Paperspace Collaborators API](https://apis.io/apis/paperspace/paperspace-collaborators-api/) — The Collaborators API from Paperspace — 2 operation(s) for collaborators.
- [Paperspace Custom Templates API](https://apis.io/apis/paperspace/paperspace-custom-templates-api/) — The Custom Templates API from Paperspace — 2 operation(s) for custom templates.
- [Paperspace Dataset Versions API](https://apis.io/apis/paperspace/paperspace-dataset-versions-api/) — The Dataset Versions API from Paperspace — 2 operation(s) for dataset versions.
- [Paperspace Machine Access API](https://apis.io/apis/paperspace/paperspace-machine-access-api/) — Team-member access grants on individual machines.
- [Paperspace Machine Events API](https://apis.io/apis/paperspace/paperspace-machine-events-api/) — Machine-event history stream.
- [Paperspace Machine Types API](https://apis.io/apis/paperspace/paperspace-machine-types-api/) — Region/availability lookups for machine types.
- [Paperspace OS Templates API](https://apis.io/apis/paperspace/paperspace-os-templates-api/) — The OS Templates API from Paperspace — 1 operation(s) for os templates.
- [Paperspace Private Networks API](https://apis.io/apis/paperspace/paperspace-private-networks-api/) — The Private Networks API from Paperspace — 2 operation(s) for private networks.
- [Paperspace Public IPs API](https://apis.io/apis/paperspace/paperspace-public-ips-api/) — The Public IPs API from Paperspace — 2 operation(s) for public ips.
- [Paperspace Secrets API](https://apis.io/apis/paperspace/paperspace-secrets-api/) — The Secrets API from Paperspace — 2 operation(s) for secrets.
- [Paperspace Shared Drives API](https://apis.io/apis/paperspace/paperspace-shared-drives-api/) — The Shared Drives API from Paperspace — 2 operation(s) for shared drives.
- [Paperspace Snapshots API](https://apis.io/apis/paperspace/paperspace-snapshots-api/) — The Snapshots API from Paperspace — 3 operation(s) for snapshots.
- [Paperspace Startup Scripts API](https://apis.io/apis/paperspace/paperspace-startup-scripts-api/) — The Startup Scripts API from Paperspace — 4 operation(s) for startup scripts.
- [Paperspace Storage Providers API](https://apis.io/apis/paperspace/paperspace-storage-providers-api/) — The Storage Providers API from Paperspace — 3 operation(s) for storage providers.
- [Paperspace Tags API](https://apis.io/apis/paperspace/paperspace-tags-api/) — The Tags API from Paperspace — 1 operation(s) for tags.
- [Paperspace Team Members API](https://apis.io/apis/paperspace/paperspace-team-members-api/) — The Team Members API from Paperspace — 2 operation(s) for team members.
- [Paperspace Team Secrets API](https://apis.io/apis/paperspace/paperspace-team-secrets-api/) — The Team Secrets API from Paperspace — 2 operation(s) for team secrets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Paperspace Agentic Access](https://apis.io/agentic-access/paperspace/paperspace-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Paperspace Deployment](https://apis.io/schemas/paperspace/paperspace-deployment/)
- [Paperspace Machine](https://apis.io/schemas/paperspace/paperspace-machine/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Paperspace Machine Structure](https://apis.io/json-structure/paperspace/paperspace-machine-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Paperspace Context](https://apis.io/jsonld/paperspace/paperspace-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Paperspace Vocabulary](https://apis.io/vocabularies/paperspace/paperspace-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Paperspace Create Machine Example](https://apis.io/examples/paperspace/paperspace-create-machine-example/)
- [Paperspace Upsert Deployment Example](https://apis.io/examples/paperspace/paperspace-upsert-deployment-example/)

#### Collections (54)

Postman and Open Collection request collections.

- [Paperspace Container Registries Activity API](https://apis.io/collections/paperspace/open-paperspace-activity-api/)
- [Paperspace Container Registries Activity Authentication API](https://apis.io/collections/paperspace/open-paperspace-authentication-api/)
- [Paperspace Container Registries Activity Collaborators API](https://apis.io/collections/paperspace/open-paperspace-collaborators-api/)
- [Paperspace Activity Container Registries API](https://apis.io/collections/paperspace/open-paperspace-container-registries-api/)
- [Paperspace Container Registries Activity Custom Templates API](https://apis.io/collections/paperspace/open-paperspace-custom-templates-api/)
- [Paperspace Container Registries Activity Dataset Versions API](https://apis.io/collections/paperspace/open-paperspace-dataset-versions-api/)
- [Paperspace Container Registries Activity Datasets API](https://apis.io/collections/paperspace/open-paperspace-datasets-api/)
- [Paperspace Container Registries Activity Deployments API](https://apis.io/collections/paperspace/open-paperspace-deployments-api/)
- [Paperspace Container Registries Activity Machine Access API](https://apis.io/collections/paperspace/open-paperspace-machine-access-api/)
- [Paperspace Container Registries Activity Machine Events API](https://apis.io/collections/paperspace/open-paperspace-machine-events-api/)
- [Paperspace Container Registries Activity Machine Types API](https://apis.io/collections/paperspace/open-paperspace-machine-types-api/)
- [Paperspace Container Registries Activity Machines API](https://apis.io/collections/paperspace/open-paperspace-machines-api/)
- [Paperspace Container Registries Activity Models API](https://apis.io/collections/paperspace/open-paperspace-models-api/)
- [Paperspace Networking API](https://apis.io/collections/paperspace/open-paperspace-networking-api/)
- [Paperspace Container Registries Activity OS Templates API](https://apis.io/collections/paperspace/open-paperspace-os-templates-api/)
- [Paperspace Container Registries Activity Private Networks API](https://apis.io/collections/paperspace/open-paperspace-private-networks-api/)
- [Paperspace Container Registries Activity Projects API](https://apis.io/collections/paperspace/open-paperspace-projects-api/)
- [Paperspace Container Registries Activity Public IPs API](https://apis.io/collections/paperspace/open-paperspace-public-ips-api/)
- [Paperspace Container Registries Activity Secrets API](https://apis.io/collections/paperspace/open-paperspace-secrets-api/)
- [Paperspace Container Registries Activity Shared Drives API](https://apis.io/collections/paperspace/open-paperspace-shared-drives-api/)
- [Paperspace Container Registries Activity Snapshots API](https://apis.io/collections/paperspace/open-paperspace-snapshots-api/)
- [Paperspace Container Registries Activity Startup Scripts API](https://apis.io/collections/paperspace/open-paperspace-startup-scripts-api/)
- [Paperspace Storage API](https://apis.io/collections/paperspace/open-paperspace-storage-api/)
- [Paperspace Container Registries Activity Storage Providers API](https://apis.io/collections/paperspace/open-paperspace-storage-providers-api/)
- [Paperspace Container Registries Activity Tags API](https://apis.io/collections/paperspace/open-paperspace-tags-api/)
- …and 29 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Paperspace — jsonschema rules](https://apis.io/rules/paperspace/paperspace-jsonschema-spectral-rules/)
- [Paperspace API Rules](https://apis.io/rules/paperspace/paperspace-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Paperspace Authentication](https://apis.io/security/paperspace/paperspace-authentication/)
- [Paperspace Domain Security](https://apis.io/security/paperspace/paperspace-domain-security/)
- [Paperspace Trust Center](https://apis.io/security/paperspace/paperspace-trust-center/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Paperspace Plans Pricing](https://apis.io/plans/paperspace/paperspace-plans-pricing/)
- [Paperspace Price Estimates](https://apis.io/plans/paperspace/paperspace-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Paperspace Rate Limits](https://apis.io/rate-limits/paperspace/paperspace-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Paperspace Finops](https://apis.io/finops/paperspace/paperspace-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.paperspace.com/)
- [Documentation](https://docs.digitalocean.com/products/paperspace/)
- [Pricing](https://www.paperspace.com/pricing)
- [Support](https://www.paperspace.com/contact-sales)
- [Blog](https://blog.paperspace.com)
- [Terms of service](https://www.paperspace.com/legal/terms-of-service)
- [Privacy policy](https://www.paperspace.com/legal/privacy-policy)
- [GitHub](https://github.com/Paperspace)
- [Status](https://status.paperspace.com)

## API Evangelist rating

**Kin Score 64.2** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 61.3 |
| Contract governance | 27.3 |
| Operational transparency | 50.0 |
| Developer ergonomics | 63.1 |
| Access clarity | 84.2 |

**Agent readiness 23.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/paperspace/](https://apis.io/providers/paperspace/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Paperspace: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/paperspace/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
