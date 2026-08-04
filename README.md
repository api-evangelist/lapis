# LAPIS (lapis)

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

LAPIS (Lightweight API Specification for Intelligent Systems) is a compact, LLM-native API description format authored by Daniel Garcia (cr0hn). It is designed as the format you convert your OpenAPI specifications to when the consumer is a Large Language Model rather than a code generator or human reader. By replacing JSON/YAML structural overhead with a function-signature syntax, indentation-based sections, and centralized definitions for errors, webhooks, rate limits, and workflows, a typical LAPIS document carries the same semantic information as its OpenAPI source while consuming roughly 70-80 percent fewer tokens. LAPIS is not a runtime format and does not replace MCP, function calling, or OpenAPI itself - it is an intermediate representation optimized for AI agents that need to reason about an API inside a constrained context window.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/lapis/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API, Specification, LLM, AI Agents, OpenAPI, Token Optimization, Standards

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-06

## APIs

### LAPIS Specification
The LAPIS specification defines a token-minimal, LLM-native format for describing HTTP APIs. A LAPIS document is organized into up to seven indentation-based sections - [meta], [types], [ops], [webhooks], [errors], [limits], and [flows] - each carrying a focused slice of the API contract. The format draws its syntax from function signatures rather than nested data structures, uses scalar types (str, int, float, bool, date, datetime, file, any) with array, map, optional, and default modifiers, and centralizes cross-cutting concerns like errors and rate limits so they are described once and applied globally. The current release is version 0.1.0 (status Draft) released 2026-02-16 under the Creative Commons Attribution 4.0 license, and the specification is published in both English and Spanish.

**Human URL:** [https://github.com/cr0hn/LAPIS/blob/main/spec.en.md](https://github.com/cr0hn/LAPIS/blob/main/spec.en.md)

#### Tags:

 - Specification, LLM, OpenAPI, Standards

#### Properties

- [LAPIS Specification (English)](https://github.com/cr0hn/LAPIS/blob/main/spec.en.md)
- [LAPIS Specification (Spanish)](https://github.com/cr0hn/LAPIS/blob/main/spec.es.md)
- [Formal EBNF Grammar](https://github.com/cr0hn/LAPIS/blob/main/spec.en.md#16-formal-grammar-simplified-ebnf)
- [Changelog](https://github.com/cr0hn/LAPIS/blob/main/CHANGELOG.md)
- [Walk-Through Example (English)](https://github.com/cr0hn/LAPIS/blob/main/spec-example.en.md)
- [Walk-Through Example (Spanish)](https://github.com/cr0hn/LAPIS/blob/main/spec-example.es.md)
- [Canonical Specification Repository](https://github.com/cr0hn/LAPIS)
- [Releases](https://github.com/cr0hn/LAPIS/releases)
- [DigitalOcean Public API v2 (LAPIS)](https://github.com/cr0hn/LAPIS/blob/main/examples/DigitalOcean-public.v2.lapis)
- [DigitalOcean Public API v2 (OpenAPI Source)](https://github.com/cr0hn/LAPIS/blob/main/examples/DigitalOcean-public.v2.yaml)

## Common Properties

- [LAPIS Online Converter](https://cr0hn.github.io/LAPIS/)
- [Specification (English)](https://github.com/cr0hn/LAPIS/blob/main/spec.en.md)
- [Specification (Spanish)](https://github.com/cr0hn/LAPIS/blob/main/spec.es.md)
- [Getting Started](https://github.com/cr0hn/LAPIS#getting-started)
- [LAPIS Repository](https://github.com/cr0hn/LAPIS)
- [Changelog](https://github.com/cr0hn/LAPIS/blob/main/CHANGELOG.md)
- [License (CC BY 4.0)](https://github.com/cr0hn/LAPIS/blob/main/LICENSE)
- [Code of Conduct](https://github.com/cr0hn/LAPIS/blob/main/CODE_OF_CONDUCT.md)
- [Security Policy](https://github.com/cr0hn/LAPIS/blob/main/SECURITY.md)
- [Contributing Guide](https://github.com/cr0hn/LAPIS/blob/main/CONTRIBUTING.md)
- [lapis CLI (lapis-spec on PyPI)](https://pypi.org/project/lapis-spec/)
- [lapis-spec Python Package](https://pypi.org/project/lapis-spec/)
- [LAPIS Visual Studio Code Extension](https://github.com/cr0hn/LAPIS/tree/main/tools/ides/vscode)
- [Browser-Based OpenAPI to LAPIS Converter](https://cr0hn.github.io/LAPIS/)
- [Issue Tracker](https://github.com/cr0hn/LAPIS/issues)

## Features

| Name | Description |
|------|-------------|
| Function-Signature Syntax for APIs | LAPIS uses operation headers shaped like function signatures (operation_name METHOD /path), input parameters prefixed with > and outputs prefixed with <, so an LLM reads each endpoint as a callable rather than as a deeply nested JSON object. |
| Seven-Section Document Model | A LAPIS document is composed of up to seven sections in a fixed order - [meta], [types], [ops], [webhooks], [errors], [limits], and [flows] - with [meta] and [ops] required and the remainder optional based on what the API actually exposes. |
| Centralized Error Definitions | Errors are declared once in [errors] using HTTP code plus a snake_case identifier, optionally bound to specific operations via @ops:name1,name2, eliminating the per-operation duplication of 400/401/404/429 responses that bloats OpenAPI documents. |
| First-Class Webhook Triggers | The [webhooks] section captures both the payload shape and the trigger condition (lines prefixed with !) that fires the event, giving an LLM the why of an event rather than only the what that OpenAPI delivers. |
| Structured Rate Limits and Quotas | The [limits] section expresses rate limits, quotas, body size caps, batch size caps, and tiered plan blocks as first-class declarative fields with scope annotations like @key, @global, @ip, @user, and @op:operation_name. |
| Multi-Step Workflow Flows | The [flows] section describes how operations chain together using step1 -> step2 -> step3 notation, with branches (\|), loops (*), waits (...(condition)), and inter-step data passing (op.field -> next_op(field)) so an agent learns canonical usage patterns alongside individual endpoints. |
| Field Versioning and Deprecation | Field-level @since:X.Y annotations let an LLM determine whether a given field exists at the API version declared in [meta], and @deprecated optionally followed by a quoted note marks fields and operations that should not be used by new integrations. |
| Operation Modifiers | Operations can carry +paginated, +deprecated, +idempotent, and +stream modifiers appended after the path, signaling pagination, retry safety, streaming response semantics, and deprecation status without verbose extension blocks. |
| Inline Object Types | Types used by only a single operation can be inlined directly in the parameter list using {field: type, field: type} or [{field: type}] notation, avoiding pollution of [types] with single-use schemas. |
| 70-80 Percent Token Reduction | For a representative mid-size API (11 operations, 8 types, 3 webhooks, 10 errors, limits, 4 flows), LAPIS measures roughly 1,500 tokens versus 6,500 for the equivalent OpenAPI YAML, a 0.23x ratio driven primarily by removing irrelevant metadata, repeated error definitions, and JSON/YAML key restatement. |
| Deterministic OpenAPI Conversion | Section 14 of the spec defines field-by-field rules for converting OpenAPI 3.x into LAPIS, covering info, servers, securitySchemes, components.schemas, paths, webhooks, x-rateLimit and x-quota extensions, and links, making the conversion fully automatable. |
| Formal EBNF Grammar | The specification ships a simplified EBNF grammar covering all seven sections, type expressions, modifiers, annotations, comments, and primitive lexical tokens, providing a normative reference for tool authors building parsers, linters, and highlighters. |
| Bilingual Specification | The LAPIS specification is published in parallel English (spec.en.md) and Spanish (spec.es.md) editions, with matching walk-through examples (spec-example.en.md and spec-example.es.md) that narrate a sample Invoice Service API in both languages. |

## Use Cases

| Name | Description |
|------|-------------|
| Reducing LLM Context Cost | Engineering teams whose AI features pass an OpenAPI specification into prompts on every call convert the spec to LAPIS once and pass the smaller LAPIS document instead, reducing per-call token spend by roughly 70-80 percent on the API description portion of the context window. |
| Powering AI Coding Assistants | AI coding assistants that need to reason about a third-party API (generating client code, debugging a failing call, suggesting an endpoint) consume LAPIS as the API context layer, freeing more of the context window for the actual user prompt and conversation history. |
| Multi-Step API Agent Planning | AI agents executing multi-step API workflows (create customer, create invoice, send invoice, await payment webhook) load a LAPIS document with a populated [flows] section so the planner has canonical workflow templates rather than having to infer chaining from individual operation descriptions. |
| Webhook-Aware Integrations | Integration platforms that build webhook receivers use the [webhooks] section's trigger conditions (!) and headers (@header:X-Event-ID) to generate signature verification and event dispatch logic that knows when each event should fire and what identifying headers to expect. |
| Plan-Aware Rate Limit Enforcement | Client SDKs and gateway integrations consume the [limits] section to configure backoff, request-throttling, and quota tracking per plan tier (free, pro, enterprise) and per scope (@key, @user, @op:name) without reading provider documentation in prose. |
| Specification Linting and Validation | Tooling vendors and platform teams enforce LAPIS-conformant documents by validating against the EBNF grammar in spec section 16, catching missing required sections, invalid type expressions, and malformed annotations before the document is shipped to downstream consumers. |
| Cross-Provider API Comparison | Because LAPIS strips presentation overhead and centralizes errors, limits, and flows, two LAPIS documents from different providers can be diffed and compared more directly than two OpenAPI specifications. |
| Onboarding Documentation for Internal APIs | Platform teams generate LAPIS from internal OpenAPI sources to provide on-call engineers and product stakeholders a quickly readable, function-signature view of the company's services alongside the long-form OpenAPI documentation. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAPI 3.0 and 3.1 | OpenAPI is the canonical source format for LAPIS. The lapis-spec Python tool ingests OpenAPI 3.0.x and 3.1.x in JSON or YAML, resolves $ref including circular references, flattens allOf/oneOf/anyOf, deduplicates inline versus named types, and emits a LAPIS document. |
| PyPI (lapis-spec) | The reference command-line converter is published to PyPI as lapis-spec and exposes a lapis console script. Installation is pip install lapis-spec or uv pip install lapis-spec, and the CLI accepts -i/--input, -o/--output, and --no-validate flags. |
| Visual Studio Code | The LAPIS Language extension (publisher lapis-spec, identifier lapis-lang) provides syntax highlighting for .lapis files, including section headers, scalar types, modifiers, IO markers, annotations, bracket matching, auto-closing pairs, and section folding. |
| Web Browser Converter | A static JavaScript single-page application at https://cr0hn.github.io/LAPIS/ runs the OpenAPI to LAPIS conversion entirely in the browser via converter.js, highlighter.js, and app.js, supporting drag-and-drop, paste, copy, and download of .lapis files. |
| MCP and Function Calling | LAPIS is positioned alongside (not as a replacement for) MCP and function calling. A LAPIS document is the context-layer description an LLM reads to understand an API; MCP servers and function-calling schemas remain the runtime invocation layer for actually executing operations. |
| Creative Commons Attribution 4.0 | The specification text is licensed under CC BY 4.0, allowing adaptation, distribution, and commercial use provided attribution is given. The reference tooling (lapis-spec Python package) is MIT licensed, and the VS Code extension is CC BY 4.0. |
| GitHub Pages | The browser-based converter is hosted on GitHub Pages from the cr0hn/LAPIS repository at https://cr0hn.github.io/LAPIS/, making it accessible without local installation or API keys. |

## Artifacts

Machine-readable artifacts modeling the LAPIS specification.

### JSON Schema

- [LAPIS Document Schema](json-schema/lapis-document-schema.json)

### JSON Structure

- [LAPIS Document Structure](json-structure/lapis-document-structure.json)

### JSON-LD

- [LAPIS Context](json-ld/lapis-context.jsonld)

### Examples

- [Invoice Service (Full Specification Example)](examples/lapis-invoice-service-example.lapis)
- [Meta Section](examples/lapis-meta-section-example.lapis)
- [Types Section](examples/lapis-types-section-example.lapis)
- [Operations Section](examples/lapis-ops-section-example.lapis)
- [Webhooks Section](examples/lapis-webhooks-section-example.lapis)
- [Errors Section](examples/lapis-errors-section-example.lapis)
- [Limits Section](examples/lapis-limits-section-example.lapis)
- [Flows Section](examples/lapis-flows-section-example.lapis)

## Vocabulary

- [LAPIS Vocabulary](vocabulary/lapis-vocabulary.yml) — Normative vocabulary of LAPIS v0.1.0 covering 7 sections, 8 scalar types, 4 operation modifiers, 10 annotations, 5 authentication types, 5 scopes, 4 rate-limit windows, 4 quota periods, 6 flow operators, and the full ecosystem of reference tooling (lapis-spec CLI, online converter, VS Code extension)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
