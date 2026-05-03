# tRPC

tRPC is a TypeScript framework for building end-to-end typesafe APIs without code generation or schemas. It leverages TypeScript's type inference to provide full static typesafety and autocompletion between client and server, with zero runtime dependencies. tRPC v11 supports queries, mutations, and subscriptions via HTTP GET/POST and WebSocket adapters.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml)

## APIs

### tRPC HTTP Protocol

tRPC servers expose typed procedures as HTTP endpoints:

- **Queries** — HTTP GET, read-only, support batching and caching
- **Mutations** — HTTP POST, write operations with side effects
- **Subscriptions** — WebSocket or SSE for real-time updates

**HTTP Protocol Details:**
- `GET /{procedure}?input=...` — Invoke a query with JSON-encoded input
- `POST /{procedure}` — Invoke a mutation with JSON body
- `POST /batch` — Execute multiple procedures in one request
- **Authentication:** Bearer token for protected procedures

**Server Adapters:** Standalone, Express, Fastify, Next.js, AWS Lambda, Fetch/Edge

- **Documentation:** [trpc.io/docs](https://trpc.io/docs)
- **GitHub:** [github.com/trpc/trpc](https://github.com/trpc/trpc)
- **NPM:** [@trpc/server](https://www.npmjs.com/package/@trpc/server)

## Artifacts

| Type | File |
|---|---|
| OpenAPI Spec | [openapi/trpc-openapi.yml](openapi/trpc-openapi.yml) |
| Spectral Rules | [rules/trpc-rules.yml](rules/trpc-rules.yml) |
| Naftiko Capabilities | [capabilities/typesafe-api-integration.yaml](capabilities/typesafe-api-integration.yaml) |
| Shared Capability | [capabilities/shared/trpc-api.yaml](capabilities/shared/trpc-api.yaml) |
| Procedure JSON Schema | [json-schema/trpc-procedure-schema.json](json-schema/trpc-procedure-schema.json) |
| Error JSON Schema | [json-schema/trpc-error-schema.json](json-schema/trpc-error-schema.json) |
| Router Structure | [json-structure/trpc-router-structure.json](json-structure/trpc-router-structure.json) |
| JSON-LD Context | [json-ld/trpc-context.jsonld](json-ld/trpc-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/trpc-vocabulary.yml](vocabulary/trpc-vocabulary.yml) |

## Capabilities

### Typesafe API Integration (`capabilities/typesafe-api-integration.yaml`)

Workflow capability for integrating with tRPC-based backends. Enables AI agents and automation workflows to call tRPC servers via standard HTTP without requiring TypeScript clients.

- **REST port:** 8080
- **MCP port:** 9090
- **Tools:** 4 tools (query-procedure, mutation-procedure, batch-procedures, health-check)

## Tags

- API Framework
- BFF
- End-to-End Type Safety
- RPC
- TypeScript

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
