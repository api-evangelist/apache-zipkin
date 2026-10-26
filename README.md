# Apache Zipkin (apache-zipkin)

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

Apache Zipkin is a distributed tracing system that helps gather timing data needed to troubleshoot latency problems in service architectures. It manages both the collection and lookup of tracing data through a collector and query service. Zipkin provides a REST API, web UI, and multiple storage backends (Cassandra, Elasticsearch, MySQL). It supports the B3 propagation format and is compatible with OpenZipkin instrumentation libraries. Originally created at Twitter, it is now maintained as an open-source project.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-zipkin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-zipkin/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Distributed Tracing
- Microservices
- Monitoring
- Observability
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Zipkin REST API

The Zipkin REST API v2 provides endpoints for querying trace data, service names, span names, and dependencies. Key endpoints include GET /api/v2/services (list services), GET /api/v2/spans (list span names for a service), GET /api/v2/traces (search traces by service, span, tags, duration), GET /api/v2/trace/{traceId} (get a specific trace), and GET /api/v2/dependencies (service dependency graph). Span reporting uses POST /api/v2/spans for JSON format or POST /api/v2/spans for Thrift format.

- **Human URL:** [https://zipkin.io/zipkin-api/](https://zipkin.io/zipkin-api/)

#### Tags

- REST
- Distributed Tracing
- Monitoring
- Observability

#### Properties

- [Documentation](https://zipkin.io/zipkin-api/)
- [OpenAPI](https://raw.githubusercontent.com/openzipkin/zipkin-api/master/zipkin2-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-zipkin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-zipkin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/openzipkin/zipkin)
- [Documentation](https://zipkin.io/pages/documentation.html)
- [Portal](https://zipkin.io/)
- [Getting Started](https://zipkin.io/pages/quickstart.html)
- [Release Notes](https://github.com/openzipkin/zipkin/releases)
- [Support](https://gitter.im/openzipkin/zipkin)
- [Terms of Service](https://www.apache.org/licenses/)
- [SDK](https://pypi.org/project/py_zipkin/)
- [SDK](https://search.maven.org/search?q=io.zipkin)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
