# tRPC (trpc)

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
