# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/4.0.3/gradle-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/4.0.3/gradle-plugin/packaging-oci-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/4.0.3/reference/web/servlet.html)
* [HTTP Client](https://docs.spring.io/spring-boot/4.0.3/reference/io/rest-client.html#io.rest-client.restclient)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/4.0.3/reference/using/devtools.html)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/4.0.3/specification/configuration-metadata/annotation-processor.html)
* [Docker Compose Support](https://docs.spring.io/spring-boot/4.0.3/reference/features/dev-services.html#features.dev-services.docker-compose)
* [SpringDoc OpenAPI](https://springdoc.org/)
* [Spring Data JDBC](https://docs.spring.io/spring-boot/4.0.3/reference/data/sql.html#data.sql.jdbc)
* [Liquibase Migration](https://docs.spring.io/spring-boot/4.0.3/how-to/data-initialization.html#howto.data-initialization.migration-tool.liquibase)
* [OpenAI](https://docs.spring.io/spring-ai/reference/api/chat/openai-chat.html)
* [JDBC Chat Memory Repository](https://docs.spring.io/spring-ai/reference/api/chat-memory.html)
* [PGvector Vector Database](https://docs.spring.io/spring-ai/reference/api/vectordbs/pgvector.html)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [SpringDoc OpenAPI](https://github.com/springdoc/springdoc-openapi-demos/)
* [Using Spring Data JDBC](https://github.com/spring-projects/spring-data-examples/tree/main/jdbc/basics)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

### Docker Compose support
This project contains a Docker Compose file named `compose.yaml`.
In this file, the following services have been defined:

* pgvector: [`pgvector/pgvector:pg16`](https://hub.docker.com/r/pgvector/pgvector)

Please review the tags of the used images and set them to the same as you're running in production.

