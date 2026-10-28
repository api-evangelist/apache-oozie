# Apache Oozie

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

Apache Oozie is a workflow scheduler system for managing Apache Hadoop jobs. It enables users to define workflows as directed acyclic graphs (DAGs) of actions including MapReduce, Pig, Hive, Sqoop, and custom Java/shell steps. Coordinator jobs trigger workflows based on time schedules or data availability, while bundle jobs group multiple coordinators. Oozie provides a REST API for job submission, lifecycle management, monitoring, and system administration. Governed by the Apache Software Foundation under the Apache License 2.0, written in Java.

**Areas:** Workflows · Hadoop · Orchestration · Scheduling · Big Data · Apache · Java · Open Source

## Apache Oozie on APIs.io

Everything profiled for Apache Oozie is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apache-oozie/](https://apis.io/providers/apache-oozie/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Apache Oozie Admin API](https://apis.io/apis/apache-oozie/apache-oozie-admin-api/) — System administration, configuration, and monitoring
- [Apache Oozie Job API](https://apis.io/apis/apache-oozie/apache-oozie-job-api/) — Single job lifecycle management and information retrieval
- [Apache Oozie Jobs API](https://apis.io/apis/apache-oozie/apache-oozie-jobs-api/) — Job submission and bulk management
- [Apache Oozie Versions API](https://apis.io/apis/apache-oozie/apache-oozie-versions-api/) — Supported protocol version discovery

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apache Oozie Agentic Access](https://apis.io/agentic-access/apache-oozie/apache-oozie-agentic-access/)

#### JSON Schema (8)

The data models the API reads and writes.

- [BuildVersion](https://apis.io/schemas/apache-oozie/apache-oozie-build-version/)
- [JobAction](https://apis.io/schemas/apache-oozie/apache-oozie-job-action/)
- [JobId](https://apis.io/schemas/apache-oozie/apache-oozie-job-id/)
- [JobInfo](https://apis.io/schemas/apache-oozie/apache-oozie-job-info/)
- [JobList](https://apis.io/schemas/apache-oozie/apache-oozie-job-list/)
- [SystemMetrics](https://apis.io/schemas/apache-oozie/apache-oozie-system-metrics/)
- [SystemStatus](https://apis.io/schemas/apache-oozie/apache-oozie-system-status/)
- [ValidationResult](https://apis.io/schemas/apache-oozie/apache-oozie-validation-result/)

#### JSON Structure (8)

Data models expressed in JSON Structure.

- [Apache Oozie Build Version Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-build-version-structure/)
- [Apache Oozie Job Action Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-job-action-structure/)
- [Apache Oozie Job Id Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-job-id-structure/)
- [Apache Oozie Job Info Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-job-info-structure/)
- [Apache Oozie Job List Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-job-list-structure/)
- [Apache Oozie System Metrics Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-system-metrics-structure/)
- [Apache Oozie System Status Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-system-status-structure/)
- [Apache Oozie Validation Result Structure](https://apis.io/json-structure/apache-oozie/apache-oozie-validation-result-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apache Oozie Context](https://apis.io/jsonld/apache-oozie/apache-oozie-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Apache Oozie Vocabulary](https://apis.io/vocabularies/apache-oozie/apache-oozie-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Apache Oozie Build Version Example](https://apis.io/examples/apache-oozie/apache-oozie-build-version-example/)
- [Apache Oozie Job Action Example](https://apis.io/examples/apache-oozie/apache-oozie-job-action-example/)
- [Apache Oozie Job Id Example](https://apis.io/examples/apache-oozie/apache-oozie-job-id-example/)
- [Apache Oozie Job Info Example](https://apis.io/examples/apache-oozie/apache-oozie-job-info-example/)
- [Apache Oozie Job List Example](https://apis.io/examples/apache-oozie/apache-oozie-job-list-example/)
- [Apache Oozie System Metrics Example](https://apis.io/examples/apache-oozie/apache-oozie-system-metrics-example/)
- [Apache Oozie System Status Example](https://apis.io/examples/apache-oozie/apache-oozie-system-status-example/)
- [Apache Oozie Validation Result Example](https://apis.io/examples/apache-oozie/apache-oozie-validation-result-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [Apache Oozie REST Admin API](https://apis.io/collections/apache-oozie/open-apache-oozie-admin-api/)
- [Apache Oozie REST Admin Job API](https://apis.io/collections/apache-oozie/open-apache-oozie-job-api/)
- [Apache Oozie REST Admin Jobs API](https://apis.io/collections/apache-oozie/open-apache-oozie-jobs-api/)
- [Apache Oozie REST Admin Versions API](https://apis.io/collections/apache-oozie/open-apache-oozie-versions-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Apache Oozie — jsonschema rules](https://apis.io/rules/apache-oozie/apache-oozie-jsonschema-spectral-rules/)
- [Apache Oozie API Rules](https://apis.io/rules/apache-oozie/apache-oozie-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Apache Oozie Domain Security](https://apis.io/security/apache-oozie/apache-oozie-domain-security/)
- [Apache Oozie Vulnerability Disclosure](https://apis.io/security/apache-oozie/apache-oozie-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apache Oozie Plans Pricing](https://apis.io/plans/apache-oozie/apache-oozie-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apache Oozie Rate Limits](https://apis.io/rate-limits/apache-oozie/apache-oozie-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apache Oozie Finops](https://apis.io/finops/apache-oozie/apache-oozie-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://apache.org)
- [Documentation](https://oozie.apache.org/docs/5.2.1/)
- [Getting started](https://oozie.apache.org/docs/5.2.1/DG_QuickStart.html)
- [Support](https://oozie.apache.org/mailing-lists.html)
- [Terms of service](https://www.apache.org/licenses/LICENSE-2.0)
- [GitHub](https://github.com/apache)

## API Evangelist rating

**Kin Score 32.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 55.7 |
| Contract governance | 13.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 18.4 |

**Agent readiness 20.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apache-oozie/](https://apis.io/providers/apache-oozie/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apache Oozie: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apache-oozie/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
