# Spring Data (spring-data)

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

Spring Data's mission is to provide a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store. It makes it easy to use data access technologies, relational and non-relational databases, map-reduce frameworks, and cloud-based data services. This is an umbrella project which contains many subprojects that are specific to a given database.

**APIs.json:** [https://spring.io/projects/spring-data](https://spring.io/projects/spring-data)

## Scope

- **Type:** Index

## Tags

- Data Access
- Database
- Framework
- Java
- JPA
- MongoDB
- ORM
- Redis
- REST
- Spring

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Spring Data REST

Exports Spring Data repositories as hypermedia-driven RESTful resources automatically. Provides HATEOAS-compliant endpoints with HAL browser, pagination, sorting, projections, and custom event hooks.

- **Human URL:** [https://spring.io/projects/spring-data-rest](https://spring.io/projects/spring-data-rest)
- **Base URL:** `http://localhost:8080`

#### Tags

- HATEOAS
- HAL
- Hypermedia
- Repository
- REST

#### Properties

- [Documentation](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-rest)
- [API Reference](https://docs.spring.io/spring-data/rest/docs/current/api/)
- [Getting Started](https://spring.io/guides/gs/accessing-data-rest/)
- [OpenAPI](openapi/spring-data-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/spring-data-paged-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spring-data-hal-resource-structure.json)

### Spring Data JPA

Simplifies the development of creating a JPA-based data access layer. Reduces boilerplate code and provides powerful query derivation, named queries, and specification-based querying on top of JPA/Hibernate.

- **Human URL:** [https://spring.io/projects/spring-data-jpa](https://spring.io/projects/spring-data-jpa)
- **Base URL:** `http://localhost:8080`

#### Tags

- Database
- Hibernate
- JPA
- Persistence
- Repository

#### Properties

- [Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-jpa)
- [API Reference](https://docs.spring.io/spring-data/jpa/docs/current/api/)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-jpa)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data MongoDB

Provides a Spring-based programming model for MongoDB. Simplifies document operations, offers repository support, geo-spatial queries, GridFS, and full-text search integration with Spring's template pattern.

- **Human URL:** [https://spring.io/projects/spring-data-mongodb](https://spring.io/projects/spring-data-mongodb)
- **Base URL:** `http://localhost:8080`

#### Tags

- Document Database
- MongoDB
- NoSQL

#### Properties

- [Documentation](https://docs.spring.io/spring-data/mongodb/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-mongodb)
- [API Reference](https://docs.spring.io/spring-data/mongodb/docs/current/api/)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-mongodb)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data Redis

Easy configuration and access to Redis from Spring applications. Provides low-level and high-level abstractions for storing, reading, querying data. Supports both reactive and imperative programming models.

- **Human URL:** [https://spring.io/projects/spring-data-redis](https://spring.io/projects/spring-data-redis)
- **Base URL:** `http://localhost:8080`

#### Tags

- Cache
- Key-Value Store
- Pub/Sub
- Redis

#### Properties

- [Documentation](https://docs.spring.io/spring-data/redis/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-redis)
- [API Reference](https://docs.spring.io/spring-data/redis/docs/current/api/)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-redis)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data Cassandra

Provides Spring-based programming model and repository support for Apache Cassandra. Offers CassandraTemplate, repository abstraction, query derivation, and reactive programming support with Project Reactor.

- **Human URL:** [https://spring.io/projects/spring-data-cassandra](https://spring.io/projects/spring-data-cassandra)
- **Base URL:** `http://localhost:8080`

#### Tags

- Cassandra
- Distributed Database
- NoSQL

#### Properties

- [Documentation](https://docs.spring.io/spring-data/cassandra/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-cassandra)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-cassandra)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data Neo4j

Spring-based programming model for Neo4j graph database. Provides repository support, object-graph mapping, Cypher query derivation, and reactive Neo4j integration with full Spring ecosystem compatibility.

- **Human URL:** [https://spring.io/projects/spring-data-neo4j](https://spring.io/projects/spring-data-neo4j)
- **Base URL:** `http://localhost:8080`

#### Tags

- Graph Database
- Neo4j
- NoSQL

#### Properties

- [Documentation](https://docs.spring.io/spring-data/neo4j/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-neo4j)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-neo4j)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Data Elasticsearch

Spring Data module for Elasticsearch search engine. Provides ElasticsearchTemplate, repository abstraction, index management, full-text search queries, and reactive Elasticsearch client support.

- **Human URL:** [https://spring.io/projects/spring-data-elasticsearch](https://spring.io/projects/spring-data-elasticsearch)
- **Base URL:** `http://localhost:8080`

#### Tags

- Elasticsearch
- Full-Text Search
- Search Engine

#### Properties

- [Documentation](https://docs.spring.io/spring-data/elasticsearch/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-elasticsearch)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-elasticsearch)
- [Postman Collection](collections/spring-data-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-data-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io/projects/spring-data)
- [Blog](https://spring.io/blog/category/data)
- [GitHub Organization](https://github.com/spring-projects)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-data)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Maven  Repository](https://mvnrepository.com/search?q=spring-data)
- [Releases](https://github.com/spring-projects/spring-data-commons/releases)
- [Issues](https://github.com/spring-projects/spring-data-commons/issues)
- [Changelog](https://github.com/spring-projects/spring-data-commons/blob/main/CHANGELOG.adoc)

## Maintainers

**FN:** Spring Team
**Email:** spring-data@pivotal.io
