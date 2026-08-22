# Crossref (crossref)

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

Crossref is a non-profit organization that provides digital infrastructure for scholarly communications. Best known for Digital Object Identifier (DOI) registration, Crossref also operates a public REST API offering searchable, filterable access to metadata for tens of millions of scholarly works, journals, members, funders, prefixes, types, licenses, and DOI registration agency information. The Crossref REST API supports free-form queries, field queries, filters, facets, deep-paging cursors, and selection of specific elements, and is used by reference managers, repositories, discovery layers, and analytics platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Citations
- DOI
- Funders
- Identifiers
- Journals
- Licenses
- Members
- Metadata
- Open Access
- ORCID
- Prefixes
- Publishers
- Reference Linking
- ROR
- Scholarly

## Timestamps

- **Created:** 2024-07-02
- **Modified:** 2026-05-19

## APIs

### Crossref REST API

The Crossref REST API is a public, read-only metadata API that provides programmatic access to Crossref's database of scholarly content. Endpoints expose works, journals, members, funders, types, licenses, prefixes, and DOI registration agency lookups, with rich query, filter, facet, sort, select, and cursor-based deep paging capabilities. No sign-up is required, but consumers are encouraged to use the polite pool by including a mailto query parameter or User-Agent contact for higher reliability.

- **Human URL:** [https://www.crossref.org/documentation/retrieve-metadata/rest-api/](https://www.crossref.org/documentation/retrieve-metadata/rest-api/)
- **Base URL:** `https://api.crossref.org`

#### Tags

- Agency
- Funders
- Journals
- Licenses
- Members
- Metadata
- Prefixes
- Types
- Works

#### Properties

- [Documentation](https://www.crossref.org/documentation/retrieve-metadata/rest-api/)
- [Swagger U I](https://api.crossref.org/swagger-ui/)
- [Polite Pool](https://www.crossref.org/documentation/retrieve-metadata/rest-api/tips-for-using-the-crossref-rest-api/#etiquette)
- [Tips](https://www.crossref.org/documentation/retrieve-metadata/rest-api/tips-for-using-the-crossref-rest-api/)
- [OpenAPI](openapi/crossref-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/crossref.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crossref.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/crossref-rules.yml)
- [Capabilities](capabilities/crossref-capabilities.yml)
- [JSON Schema](json-schema/crossref-work-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/crossref-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/crossref)
- [Vocabulary](vocabulary/crossref-vocabulary.yml)
- [JSON-LD](json-ld/crossref-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/crossref-work-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://www.crossref.org/)
- [Documentation](https://www.crossref.org/documentation/)
- [A P I Documentation](https://www.crossref.org/documentation/retrieve-metadata/rest-api/)
- [Blog](https://www.crossref.org/blog/)
- [GitHub Organization](https://github.com/CrossRef)
- [Status Page](https://status.crossref.org/)
- [Community](https://community.crossref.org/)
- [Terms of Service](https://www.crossref.org/operations-and-sustainability/terms/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
