# Apache Zipkin (apache-zipkin)
Apache Zipkin is a distributed tracing system that helps gather timing data needed to troubleshoot latency problems in service architectures. It provides a REST API, web UI, and multiple storage backends for collecting and querying distributed trace data.

**URL:** [https://zipkin.io/](https://zipkin.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Tracing, Microservices, Monitoring, Observability, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Zipkin REST API
REST API v2 for querying trace data including GET /api/v2/services, GET /api/v2/traces, GET /api/v2/trace/{traceId}, and GET /api/v2/dependencies for service dependency graphs.

**Human URL:** [https://zipkin.io/zipkin-api/](https://zipkin.io/zipkin-api/)

#### Tags:

 - REST, Distributed Tracing, Monitoring, Observability

#### Properties

- [Documentation](https://zipkin.io/zipkin-api/)
- [OpenAPI](https://raw.githubusercontent.com/openzipkin/zipkin-api/master/zipkin2-api.yaml)

## Common Properties

- [GitHubRepository](https://github.com/openzipkin/zipkin)
- [Documentation](https://zipkin.io/pages/documentation.html)
- [Portal](https://zipkin.io/)
- [GettingStarted](https://zipkin.io/pages/quickstart.html)
- [ReleaseNotes](https://github.com/openzipkin/zipkin/releases)
- [Support](https://gitter.im/openzipkin/zipkin)
- [TermsOfService](https://www.apache.org/licenses/)
- [Python SDK](https://pypi.org/project/py_zipkin/)
- [Java SDK](https://search.maven.org/search?q=io.zipkin)

## Features

| Name | Description |
|------|-------------|
| Distributed Trace Collection | Collect timing and metadata for distributed service calls with B3 propagation. |
| Trace Query and Visualization | Web UI and REST API for searching and visualizing traces with latency analysis. |
| Service Dependency Graph | Automatic service call graph generation from collected trace data. |
| Multiple Storage Backends | Cassandra, Elasticsearch, and MySQL storage backends. |
| OpenTelemetry Compatible | Accepts OTLP/Zipkin spans from OpenTelemetry instrumented services. |
| B3 Propagation | Standard B3 trace propagation headers for distributed context passing. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Latency Troubleshooting | Identify bottlenecks and slow service calls in distributed architectures. |
| Service Dependency Mapping | Automatically discover and visualize service-to-service call graphs. |
| Performance Regression Detection | Compare trace data before and after deployments to detect regressions. |
| Root Cause Analysis | Follow distributed call chains to identify root causes of errors. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Cloud Sleuth | Spring Boot auto-instrumentation for trace propagation and Zipkin reporting. |
| Brave | Java instrumentation library for adding Zipkin tracing to Java applications. |
| Elasticsearch | Elasticsearch storage backend for scalable trace data storage. |
| Apache Cassandra | Cassandra storage backend for high-volume trace data. |
| OpenTelemetry | OpenTelemetry Zipkin exporter for OTLP traces. |
| Kafka | Kafka collector for high-throughput microservice span ingestion. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
