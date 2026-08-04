# tRPC (trpc)

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

tRPC is a TypeScript framework for building end-to-end typesafe APIs without code generation or schemas. It leverages TypeScript's type inference to provide full static typesafety and autocompletion between client and server, with zero runtime dependencies. tRPC v11 supports queries, mutations, and subscriptions via HTTP GET/POST and WebSocket adapters for Express, Fastify, Next.js, AWS Lambda, and edge runtimes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Composition
- API Framework
- BFF
- End-to-End Type Safety
- RPC
- TypeScript

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### tRPC HTTP Protocol

The tRPC HTTP API protocol surface. tRPC servers expose procedures via HTTP GET (queries) and HTTP POST (mutations). Clients use httpBatchLink to batch concurrent calls into single requests. Input is passed via JSON-encoded query parameters (GET) or request bodies (POST). Authentication uses Bearer tokens for protected procedures.

- **Human URL:** [https://trpc.io/docs/](https://trpc.io/docs/)
- **Base URL:** `https://your-server.example.com/api/trpc`

#### Tags

- API Framework
- HTTP
- RPC
- TypeScript

#### Properties

- [Documentation](https://trpc.io/docs)
- [Getting Started](https://trpc.io/docs/quickstart)
- [GitHub Repository](https://github.com/trpc/trpc)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/openapi/trpc-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/rules/trpc-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-schema/trpc-procedure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-schema/trpc-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-ld/trpc-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/vocabulary/trpc-vocabulary.yml)
- [Postman Collection](collections/trpc.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trpc.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://trpc.io/)
- [Documentation](https://trpc.io/docs)
- [GitHub Organization](https://github.com/trpc)
- [GitHub Repository](https://github.com/trpc/trpc)
- [N P M](https://www.npmjs.com/package/@trpc/server)
- [Discord](https://trpc.io/discord)
- [Twitter](https://twitter.com/alexdotjs)
- [L L Ms Txt](https://trpc.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
