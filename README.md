# Grist

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

Grist is a collaborative spreadsheet and relational database platform that combines the flexibility of spreadsheets with the power of a structured database. It provides a REST API for reading and writing table records, managing organizations, workspaces, and documents, executing SQL queries against document data, and configuring outgoing webhooks triggered by data changes. Grist is available as a cloud-hosted SaaS at getgrist.com and as an open-source self-hosted deployment via the Apache-licensed grist-core repository maintained by Grist Labs.

**Areas:** Spreadsheets · Database · Collaboration · No-Code · Data Management · Webhook · Open Source

## Grist on APIs.io

Everything profiled for Grist is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/grist/](https://apis.io/providers/grist/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Grist Attachments API](https://apis.io/apis/grist/grist-attachments-api/) — Documents may include attached files. Data records can refer to these using a column of type `Attachments`.
- [Grist Columns API](https://apis.io/apis/grist/grist-columns-api/) — Tables are structured as a collection of columns.
- [Grist Data API](https://apis.io/apis/grist/grist-data-api/) — Work with table data, using a (now deprecated) columnar format. We now recommend the `records` endpoints.
- [Grist Docs API](https://apis.io/apis/grist/grist-docs-api/) — Workspaces contain collections of Grist documents.
- [Grist Forms API](https://apis.io/apis/grist/grist-forms-api/) — The forms API from Grist — 1 operation(s) for forms.
- [Grist Orgs API](https://apis.io/apis/grist/grist-orgs-api/) — Team sites and personal spaces are called 'orgs' in the API.
- [Grist Profile API](https://apis.io/apis/grist/grist-profile-api/) — The profile API from Grist — 4 operation(s) for profile.
- [Grist Records API](https://apis.io/apis/grist/grist-records-api/) — Tables contain collections of records (also called rows).
- [Grist service accounts API](https://apis.io/apis/grist/grist-service-accounts-api/) — Impersonations to manage grist resources through REST APIs with specific rights.
- [Grist Session API](https://apis.io/apis/grist/grist-session-api/) — The session API from Grist — 2 operation(s) for session.
- [Grist Sql API](https://apis.io/apis/grist/grist-sql-api/) — Sql endpoint to query data from documents.
- [Grist Tables API](https://apis.io/apis/grist/grist-tables-api/) — Documents are structured as a collection of tables.
- [Grist Templates API](https://apis.io/apis/grist/grist-templates-api/) — The templates API from Grist — 2 operation(s) for templates.
- [Grist Users API](https://apis.io/apis/grist/grist-users-api/) — Grist users.
- [Grist Webhooks API](https://apis.io/apis/grist/grist-webhooks-api/) — Document changes can trigger requests to URLs called webhooks.
- [Grist Widgets API](https://apis.io/apis/grist/grist-widgets-api/) — The widgets API from Grist — 1 operation(s) for widgets.
- [Grist Workspaces API](https://apis.io/apis/grist/grist-workspaces-api/) — Sites can be organized into groups of documents called workspaces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Grist Agentic Access](https://apis.io/agentic-access/grist/grist-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [GristDocument](https://apis.io/schemas/grist/grist-document/)
- [GristRecord](https://apis.io/schemas/grist/grist-record/)
- [GristWebhook](https://apis.io/schemas/grist/grist-webhook/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Grist Context](https://apis.io/jsonld/grist/grist-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Grist Vocabulary](https://apis.io/vocabularies/grist/grist-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Add Records Request](https://apis.io/examples/grist/add-records-request/)
- [Create Webhook Request](https://apis.io/examples/grist/create-webhook-request/)
- [List Records Response](https://apis.io/examples/grist/list-records-response/)
- [Run Sql Request](https://apis.io/examples/grist/run-sql-request/)

#### Collections (17)

Postman and Open Collection request collections.

- [Grist attachments API](https://apis.io/collections/grist/open-grist-attachments-api/)
- [Grist attachments columns API](https://apis.io/collections/grist/open-grist-columns-api/)
- [Grist attachments data API](https://apis.io/collections/grist/open-grist-data-api/)
- [Grist attachments docs API](https://apis.io/collections/grist/open-grist-docs-api/)
- [Grist attachments forms API](https://apis.io/collections/grist/open-grist-forms-api/)
- [Grist attachments orgs API](https://apis.io/collections/grist/open-grist-orgs-api/)
- [Grist attachments profile API](https://apis.io/collections/grist/open-grist-profile-api/)
- [Grist attachments records API](https://apis.io/collections/grist/open-grist-records-api/)
- [Grist attachments service accounts API](https://apis.io/collections/grist/open-grist-service-accounts-api/)
- [Grist attachments session API](https://apis.io/collections/grist/open-grist-session-api/)
- [Grist attachments sql API](https://apis.io/collections/grist/open-grist-sql-api/)
- [Grist attachments tables API](https://apis.io/collections/grist/open-grist-tables-api/)
- [Grist attachments templates API](https://apis.io/collections/grist/open-grist-templates-api/)
- [Grist attachments users API](https://apis.io/collections/grist/open-grist-users-api/)
- [Grist attachments webhooks API](https://apis.io/collections/grist/open-grist-webhooks-api/)
- [Grist attachments widgets API](https://apis.io/collections/grist/open-grist-widgets-api/)
- [Grist attachments workspaces API](https://apis.io/collections/grist/open-grist-workspaces-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Grist — jsonschema rules](https://apis.io/rules/grist/grist-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Grist Authentication](https://apis.io/security/grist/grist-authentication/)
- [Grist Domain Security](https://apis.io/security/grist/grist-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Grist Plans Pricing](https://apis.io/plans/grist/grist-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Grist Rate Limits](https://apis.io/rate-limits/grist/grist-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Grist Finops](https://apis.io/finops/grist/grist-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.getgrist.com/)
- [Documentation](https://support.getgrist.com/)
- [Pricing](https://www.getgrist.com/pricing/)
- [Changelog](https://github.com/gristlabs/grist-core/releases)
- [Blog](https://www.getgrist.com/blog/)
- [GitHub](https://github.com/gristlabs)

## API Evangelist rating

**Kin Score 36.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 51.5 |
| Contract governance | 23.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 18.4 |

**Agent readiness 24.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
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

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/grist/](https://apis.io/providers/grist/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Grist: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/grist/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
