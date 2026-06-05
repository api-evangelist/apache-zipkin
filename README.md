# Apache Zipkin (apache-zipkin)

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
