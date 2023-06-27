# Getting Started

### How to Run and Test

* [Create new secret key and replace all YOUR_API_KEY_HERE in code with this new key](https://platform.openai.com/account/api-keys)
* `cd openai-service`
* `export JAVA_HOME=$(/usr/libexec/java_home -v 17)`
* `mvn spring-boot:run`
* Swagger Url: http://localhost:8080/swagger-ui/index.html
* [openai-test-requests.http](openai-test-requests.http)
* [docker-compose.yml](docker-compose.yml)

### Reference Documentation

For further reference, please consider the following sections:

* [https://platform.openai.com/docs/api-reference/completions](https://platform.openai.com/docs/api-reference/completions)
* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.1/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.1/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.1/reference/htmlsingle/#web)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.1.1/reference/htmlsingle/#data.sql.jpa-and-spring-data)

### Guides

The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

