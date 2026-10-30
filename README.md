# Harvard University

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

Harvard University (Cambridge, Massachusetts; founded 1636; private, Ivy League) is one of the few institutions in this cohort with a genuinely institution-operated programmable footprint rather than a borrowed one. Five surfaces are Harvard's own: the Harvard Dataverse research data repository, which runs on Harvard's own infrastructure and whose Dataverse software is written by Harvard's Institute for Quantitative Social Science and serves a live 450-path OpenAPI; the Harvard Library LibraryCloud open metadata API, unauthenticated over 12M+ bibliographic records; the Harvard Art Museums collections API; a Shibboleth identity provider registered in the InCommon federation with REFEDS SIRTFI assurance; and two Harvard Law School Library Innovation Lab surfaces, the Caselaw Access Project static bulk data and a 2026 OpenAPI 3.1 agent-skills hub. Alongside them sit five vendor tenancies that are just as real and are recorded as such rather than credited to Harvard: DASH runs on 4Science's managed DSpace behind a harvard.edu hostname, the HOLLIS catalog is an Ex Libris Primo VE instance, harvard.figshare.com is a Figshare tenancy, canvas.harvard.edu is an Instructure tenancy, and harvard.zoom.us is a Zoom tenancy. There is no unified developer program: the central HUIT API Portal exists but its catalog, its base URLs and its credentials all sit behind HarvardKey, and the whole harvard.edu Drupal estate answers automated clients with an Akamai 403.

**Areas:** University · Higher Education · Education · United States · Ivy League · Private Research University · Research Data · Research Repository · Open Metadata · OAI-PMH · Identity Federation · Library

## Harvard University on APIs.io

Everything profiled for Harvard University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/harvard/](https://apis.io/providers/harvard/)** — or go straight to one of the APIs or properties below.

### APIs (50)

- [Harvard Dataverse OAI-PMH](https://apis.io/apis/harvard/dataverse-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for Harvard Dataverse. Identify returns repositoryName "Harvard Dataverse Dataverse OAI Archive" with adminEmail…
- [Harvard Library LibraryCloud API (Open Metadata)](https://apis.io/apis/harvard/librarycloud/) — Open metadata hub aggregating Harvard bibliographic metadata (12.7M+ bib records, image records, ArchivesSpace finding aids) and returning normalized MODS…
- [Harvard Art Museums API](https://apis.io/apis/harvard/art-museums/) — REST/JSON API to the Harvard Art Museums' collections across 25 documented resources (object, person, exhibition, publication, gallery, classification,…
- [Harvard University Shibboleth Identity Provider (InCommon)](https://apis.io/apis/harvard/identity-federation/) — Harvard's SAML 2.0 identity provider, entityID https://fed.huit.harvard.edu/idp/shibboleth, registered in the InCommon federation and reachable as signed…
- [Caselaw Access Project bulk data (Harvard Library Innovation Lab)](https://apis.io/apis/harvard/caselaw-access-project/) — Harvard Law School Library Innovation Lab's digitization of US case law, served as static bulk data organized by reporter. The live REST API at api.case.law…
- [Perma.cc API (Harvard Library Innovation Lab)](https://apis.io/apis/harvard/perma/) — Perma.cc is the Harvard Law School Library Innovation Lab's link-rot service, creating permanent citable archives of web pages, and it exposes a public REST…
- [Harvard API Portal (HUIT)](https://apis.io/apis/harvard/api-portal/) — Harvard University Information Technology's central catalog of administrative APIs - Courses, Person Data Service, Library Catalog, Dining, HR Departments,…
- [Harvard DASH institutional repository (4Science-managed DSpace)](https://apis.io/apis/harvard/dash/) — DASH (Digital Access to Scholarship at Harvard) is Harvard's open-access institutional repository of 58,000+ scholarly works, exposing an open OAI-PMH 2.0…
- [HOLLIS library discovery (Ex Libris Primo VE tenancy)](https://apis.io/apis/harvard/hollis/) — HOLLIS is Harvard Library's discovery layer. hollis.harvard.edu CNAMEs to hvd.primo.exlibrisgroup.com and redirects to…
- [Harvard Figshare tenancy](https://apis.io/apis/harvard/figshare/) — harvard.figshare.com is a Figshare institutional tenancy - the host CNAMEs directly to figshare.com. This is precisely the surface that produced the…
- [Canvas LMS tenancy (Instructure)](https://apis.io/apis/harvard/canvas/) — canvas.harvard.edu CNAMEs to harvard-vanity.instructure.com. The Canvas REST API is live on that hostname and returns a well-formed JSON 401 to an anonymous…
- [Zoom tenancy](https://apis.io/apis/harvard/zoom/) — harvard.zoom.us is a Zoom institutional tenancy branded "Zoom for Harvard", and a Zoom API appears in the HUIT API Portal catalog. The account is Harvard's;…
- [Harvard University Access API](https://apis.io/apis/harvard/harvard-access-api/) — The Access API from Harvard University — 23 operation(s) for access.
- [Harvard University Actions API](https://apis.io/apis/harvard/harvard-actions-api/) — The Actions API from Harvard University — 4 operation(s) for actions.
- [Harvard University Add Files To Dataset API](https://apis.io/apis/harvard/harvard-addfilestodataset-api/) — Uploads a set of files to a dataset
- [Harvard University Add File To Dataset API](https://apis.io/apis/harvard/harvard-addfiletodataset-api/) — Uploads a file for a dataset
- [Harvard University Add Globus Files To Dataset API](https://apis.io/apis/harvard/harvard-addglobusfilestodataset-api/) — Uploads a Globus file for a dataset
- [Harvard University Admin API](https://apis.io/apis/harvard/harvard-admin-api/) — The Admin API from Harvard University — 127 operation(s) for admin.
- [Harvard University Batch API](https://apis.io/apis/harvard/harvard-batch-api/) — The Batch API from Harvard University — 3 operation(s) for batch.
- [Harvard University Builtin Users API](https://apis.io/apis/harvard/harvard-builtin-users-api/) — The Builtin Users API from Harvard University — 4 operation(s) for builtin users.
- [Harvard University Datasetfields API](https://apis.io/apis/harvard/harvard-datasetfields-api/) — The Datasetfields API from Harvard University — 1 operation(s) for datasetfields.
- [Harvard University Datasets API](https://apis.io/apis/harvard/harvard-datasets-api/) — The Datasets API from Harvard University — 102 operation(s) for datasets.
- [Harvard University Datatags API](https://apis.io/apis/harvard/harvard-datatags-api/) — The Datatags API from Harvard University — 1 operation(s) for datatags.
- [Harvard University Dataverse Featured Items API](https://apis.io/apis/harvard/harvard-dataversefeatureditems-api/) — The DataverseFeaturedItems API from Harvard University — 1 operation(s) for dataversefeatureditems.
- [Harvard University Dataverses API](https://apis.io/apis/harvard/harvard-dataverses-api/) — The Dataverses API from Harvard University — 46 operation(s) for dataverses.
- [Harvard University Edit API](https://apis.io/apis/harvard/harvard-edit-api/) — The Edit API from Harvard University — 1 operation(s) for edit.
- [Harvard University Files API](https://apis.io/apis/harvard/harvard-files-api/) — The Files API from Harvard University — 21 operation(s) for files.
- [Harvard University Guestbooks API](https://apis.io/apis/harvard/harvard-guestbooks-api/) — The Guestbooks API from Harvard University — 4 operation(s) for guestbooks.
- [Harvard University Harvest API](https://apis.io/apis/harvard/harvard-harvest-api/) — The Harvest API from Harvard University — 7 operation(s) for harvest.
- [Harvard University Inbox API](https://apis.io/apis/harvard/harvard-inbox-api/) — The Inbox API from Harvard University — 1 operation(s) for inbox.
- [Harvard University Info API](https://apis.io/apis/harvard/harvard-info-api/) — The Info API from Harvard University — 53 operation(s) for info.
- [Harvard University Ingest API](https://apis.io/apis/harvard/harvard-ingest-api/) — The Ingest API from Harvard University — 1 operation(s) for ingest.
- [Harvard University Licenses API](https://apis.io/apis/harvard/harvard-licenses-api/) — The Licenses API from Harvard University — 6 operation(s) for licenses.
- [Harvard University Localcontexts API](https://apis.io/apis/harvard/harvard-localcontexts-api/) — The Localcontexts API from Harvard University — 2 operation(s) for localcontexts.
- [Harvard University Logout API](https://apis.io/apis/harvard/harvard-logout-api/) — The Logout API from Harvard University — 1 operation(s) for logout.
- [Harvard University Mail API](https://apis.io/apis/harvard/harvard-mail-api/) — The Mail API from Harvard University — 1 operation(s) for mail.
- [Harvard University Meta API](https://apis.io/apis/harvard/harvard-meta-api/) — The Meta API from Harvard University — 2 operation(s) for meta.
- [Harvard University Metadatablocks API](https://apis.io/apis/harvard/harvard-metadatablocks-api/) — The Metadatablocks API from Harvard University — 2 operation(s) for metadatablocks.
- [Harvard University Mydata API](https://apis.io/apis/harvard/harvard-mydata-api/) — The Mydata API from Harvard University — 2 operation(s) for mydata.
- [Harvard University Notifications API](https://apis.io/apis/harvard/harvard-notifications-api/) — The Notifications API from Harvard University — 8 operation(s) for notifications.
- [Harvard University Pids API](https://apis.io/apis/harvard/harvard-pids-api/) — The Pids API from Harvard University — 6 operation(s) for pids.
- [Harvard University Replace Files In Dataset API](https://apis.io/apis/harvard/harvard-replacefilesindataset-api/) — Replace a file to a dataset
- [Harvard University Roles API](https://apis.io/apis/harvard/harvard-roles-api/) — The Roles API from Harvard University — 3 operation(s) for roles.
- [Harvard University Save Auxiliary File With Version API](https://apis.io/apis/harvard/harvard-saveauxiliaryfilewithversion-api/) — Save Auxiliary File With Version
- [Harvard University Search API](https://apis.io/apis/harvard/harvard-search-api/) — The Search API from Harvard University — 2 operation(s) for search.
- [Harvard University Upload Dataset Logo API](https://apis.io/apis/harvard/harvard-uploaddatasetlogo-api/) — Uploads a logo for a dataset
- [Harvard University Users API](https://apis.io/apis/harvard/harvard-users-api/) — The Users API from Harvard University — 10 operation(s) for users.
- [Harvard University Workflows API](https://apis.io/apis/harvard/harvard-workflows-api/) — The Workflows API from Harvard University — 1 operation(s) for workflows.
- [Harvard University External Tools API](https://apis.io/apis/harvard/harvard-external-tools-api/) — The External Tools API from Harvard University — 2 operation(s) for external tools.
- [Harvard University Send Feedback API](https://apis.io/apis/harvard/harvard-send-feedback-api/) — The Send Feedback API from Harvard University — 1 operation(s) for send feedback.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [Harvard Library LibraryCloud Item response](https://apis.io/schemas/harvard/harvard-librarycloud-item.schema/)
- [Harvard LIL Legal Ed Skills Hub persona index](https://apis.io/schemas/harvard/harvard-lil-lawskills-persona-index.schema/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Harvard Context](https://apis.io/jsonld/harvard/harvard-context/)

#### Examples (5)

Example requests and responses.

- [Harvard Dash Dspace Rest Root](https://apis.io/examples/harvard/harvard-dash-dspace-rest-root/)
- [Harvard Datacite Prefix 10.7910](https://apis.io/examples/harvard/harvard-datacite-prefix-10.7910/)
- [Harvard Dataverse Search Response](https://apis.io/examples/harvard/harvard-dataverse-search-response/)
- [Harvard Librarycloud Item Response](https://apis.io/examples/harvard/harvard-librarycloud-item-response/)
- [Harvard Lil Lawskills Personas](https://apis.io/examples/harvard/harvard-lil-lawskills-personas/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Harvard University — governance rules](https://apis.io/rules/harvard/harvard-governance-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Harvard Authentication](https://apis.io/security/harvard/harvard-authentication/)
- [Harvard Domain Security](https://apis.io/security/harvard/harvard-domain-security/)
- [Harvard Vulnerability Disclosure](https://apis.io/security/harvard/harvard-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Harvard Scopes](https://apis.io/scopes/harvard/harvard-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Harvard Plans Pricing](https://apis.io/plans/harvard/harvard-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Harvard Rate Limits](https://apis.io/rate-limits/harvard/harvard-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Harvard Finops](https://apis.io/finops/harvard/harvard-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.harvard.edu/)
- [Documentation](https://library.harvard.edu/services-tools/harvard-library-apis-datasets)
- [API reference](https://portal.apis.huit.harvard.edu/apis)
- [Support](https://www.harvard.edu/contact-harvard)
- [Blog](https://news.harvard.edu/gazette/)
- [Privacy policy](https://www.harvard.edu/privacy-statement/)
- [GitHub](https://github.com/harvard)

## API Evangelist rating

**Kin Score 34.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 47.6 |
| Contract governance | 11.4 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 28.9 |

**Agent readiness 21.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 36.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/harvard/](https://apis.io/providers/harvard/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Harvard University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/harvard/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
