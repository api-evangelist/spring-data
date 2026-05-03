# Spring Data

Spring Data's mission is to provide a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store. It makes it easy to use data access technologies, relational and non-relational databases, map-reduce frameworks, and cloud-based data services.

**URL:** https://spring.io/projects/spring-data

## Tags

Data Access, Database, Framework, Java, JPA, MongoDB, ORM, Redis, REST, Spring

## APIs

### Spring Data REST

Exports Spring Data repositories as hypermedia-driven RESTful resources automatically. Provides HATEOAS-compliant endpoints with HAL browser, pagination, sorting, projections, and custom event hooks.

**Human URL:** https://spring.io/projects/spring-data-rest
**Base URL:** http://localhost:8080

**Tags:** HATEOAS, HAL, Hypermedia, Repository, REST

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-rest)
- [API Reference](https://docs.spring.io/spring-data/rest/docs/current/api/)
- [Getting Started](https://spring.io/guides/gs/accessing-data-rest/)
- [OpenAPI](openapi/spring-data-rest-openapi.yml)
- [JSON Schema](json-schema/spring-data-paged-resource-schema.json)
- [JSON Structure](json-structure/spring-data-hal-resource-structure.json)

### Spring Data JPA

Simplifies the development of creating a JPA-based data access layer. Reduces boilerplate code and provides powerful query derivation, named queries, and specification-based querying on top of JPA/Hibernate.

**Human URL:** https://spring.io/projects/spring-data-jpa

**Tags:** Database, Hibernate, JPA, Persistence, Repository

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-jpa)
- [API Reference](https://docs.spring.io/spring-data/jpa/docs/current/api/)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.data/spring-data-jpa)

### Spring Data MongoDB

Provides a Spring-based programming model for MongoDB. Simplifies document operations, offers repository support, geo-spatial queries, GridFS, and full-text search integration.

**Human URL:** https://spring.io/projects/spring-data-mongodb

**Tags:** Document Database, MongoDB, NoSQL

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/mongodb/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-mongodb)
- [API Reference](https://docs.spring.io/spring-data/mongodb/docs/current/api/)

### Spring Data Redis

Easy configuration and access to Redis from Spring applications. Provides low-level and high-level abstractions for storing, reading, and querying data with reactive and imperative support.

**Human URL:** https://spring.io/projects/spring-data-redis

**Tags:** Cache, Key-Value Store, Pub/Sub, Redis

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/redis/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-redis)
- [API Reference](https://docs.spring.io/spring-data/redis/docs/current/api/)

### Spring Data Cassandra

Provides Spring-based programming model and repository support for Apache Cassandra. Offers CassandraTemplate, repository abstraction, and reactive programming support.

**Human URL:** https://spring.io/projects/spring-data-cassandra

**Tags:** Cassandra, Distributed Database, NoSQL

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/cassandra/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-cassandra)

### Spring Data Neo4j

Spring-based programming model for Neo4j graph database. Provides repository support, object-graph mapping, Cypher query derivation, and reactive Neo4j integration.

**Human URL:** https://spring.io/projects/spring-data-neo4j

**Tags:** Graph Database, Neo4j, NoSQL

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/neo4j/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-neo4j)

### Spring Data Elasticsearch

Spring Data module for Elasticsearch. Provides ElasticsearchTemplate, repository abstraction, index management, and full-text search query support.

**Human URL:** https://spring.io/projects/spring-data-elasticsearch

**Tags:** Elasticsearch, Full-Text Search, Search Engine

**Properties:**
- [Documentation](https://docs.spring.io/spring-data/elasticsearch/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-data-elasticsearch)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-data-rest-openapi.yml](openapi/spring-data-rest-openapi.yml) | Spring Data REST HATEOAS repository endpoints |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-data-paged-resource-schema.json](json-schema/spring-data-paged-resource-schema.json) | HAL+JSON paginated resource response schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-data-hal-resource-structure.json](json-structure/spring-data-hal-resource-structure.json) | HAL resource and paged collection structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-data-context.jsonld](json-ld/spring-data-context.jsonld) | Spring Data linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-data-list-resources-example.json](examples/spring-data-list-resources-example.json) | Paginated HAL+JSON collection response |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-data-rules.yml](rules/spring-data-rules.yml) | API design rules for Spring Data REST conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/data-access.yaml](capabilities/data-access.yaml) | Data access workflow (list, get, create, delete, search) |
| [capabilities/shared/spring-data-rest.yaml](capabilities/shared/spring-data-rest.yaml) | Shared Spring Data REST consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-data-vocabulary.yml](vocabulary/spring-data-vocabulary.yml) | Spring Data domain vocabulary and terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-data)
- [Blog](https://spring.io/blog/category/data)
- [GitHub Organization](https://github.com/spring-projects)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-data)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Maven Repository](https://mvnrepository.com/search?q=spring-data)
- [Releases](https://github.com/spring-projects/spring-data-commons/releases)
- [Issues](https://github.com/spring-projects/spring-data-commons/issues)

## Maintainers

**Name:** Spring Team  
**Email:** spring-data@pivotal.io  
**Twitter:** @springcentral  
**GitHub:** spring-projects
