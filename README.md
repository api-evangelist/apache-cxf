# Apache CXF (apache-cxf)
Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first development, full WS-* standards (WS-Security, WS-ReliableMessaging, WS-Addressing, WS-Policy), multiple transports (HTTP, JMS), and integrates with Spring Framework, OSGi/ServiceMix, and major Java EE servers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, JAX-RS, JAX-WS, Java, Open Source, REST, SOAP, WS-Security, Web Services

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache CXF
CXF provides Java APIs for building SOAP (JAX-WS) and REST (JAX-RS) web services with WSDL-first and code-first approaches, WS-* standards support, multiple data bindings (JAXB, Aegis, XMLBeans), pluggable transports (HTTP, JMS, In-VM), and code generation tools (wsdl2java, java2ws).

**Human URL:** [https://cxf.apache.org/docs/index.html](https://cxf.apache.org/docs/index.html)

#### Tags:

 - CORBA, HTTP, JAX-RS, JAX-WS, Java, JMS, REST, SOAP, WSDL, WS-Security, Web Services

#### Properties

- [Documentation](https://cxf.apache.org/docs/index.html)
- [GettingStarted](https://cxf.apache.org/docs/a-simple-jax-ws-service.html)
- [APIReference](https://cxf.apache.org/javadoc/latest/)
- [GitHubRepository](https://github.com/apache/cxf)
- [cxf-rt-frontend-jaxws (Maven)](https://mvnrepository.com/artifact/org.apache.cxf/cxf-rt-frontend-jaxws)
- [cxf-rt-frontend-jaxrs (Maven)](https://mvnrepository.com/artifact/org.apache.cxf/cxf-rt-frontend-jaxrs)
- [Spring Boot Starter JAX-RS (Maven)](https://mvnrepository.com/artifact/org.apache.cxf/cxf-spring-boot-starter-jaxrs)
- [Spring Boot Starter JAX-WS (Maven)](https://mvnrepository.com/artifact/org.apache.cxf/cxf-spring-boot-starter-jaxws)
- [Jaxrs Endpoint](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-jaxrs-endpoint-schema.json)
- [Jaxws Endpoint](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-jaxws-endpoint-schema.json)
- [Ws Security Config](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-ws-security-config-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-jaxrs-endpoint-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-jaxws-endpoint-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-ws-security-config-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-ld/apache-cxf-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-jaxrs-endpoint-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-jaxws-endpoint-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-ws-security-config-example.json)

## Common Properties

- [Portal](https://cxf.apache.org/)
- [Documentation](https://cxf.apache.org/docs/index.html)
- [GettingStarted](https://cxf.apache.org/docs/a-simple-jax-ws-service.html)
- [ReleaseNotes](https://cxf.apache.org/download.html)
- [GitHubRepository](https://github.com/apache/cxf)
- [GitHubOrganization](https://github.com/apache)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-cxf)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/vocabulary/apache-cxf-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| JAX-WS SOAP Services | Full JAX-WS implementation for building contract-first and code-first SOAP web services with WSDL support. |
| JAX-RS REST Services | Full JAX-RS implementation for building RESTful services with JSON and XML support and OpenAPI integration. |
| WS-Security | Comprehensive WS-Security support including XML Signature, XML Encryption, SAML tokens, Kerberos, and Username Tokens. |
| Multiple Transports | Supports HTTP, Servlet, JMS, In-VM, and local transports for flexible service deployment. |
| Code Generation | wsdl2java generates Java clients and server stubs from WSDL; java2ws generates WSDL and XSD from annotated Java classes. |
| Spring Integration | Deep Spring Framework integration with Spring Boot starters for rapid JAX-WS and JAX-RS service development. |
| Data Bindings | Supports JAXB 2.x, Aegis, XMLBeans, SDO, and JiBX data bindings for flexible XML/JSON marshalling. |
| WS-* Standards | Implements WS-Addressing, WS-ReliableMessaging, WS-Policy, WS-MetadataExchange, and MTOM for enterprise-grade SOAP. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise SOA | Build and expose SOAP-based service-oriented architecture services in enterprise Java applications. |
| REST API Development | Create RESTful APIs with JAX-RS annotations, OpenAPI documentation, and JSON/XML serialization. |
| Legacy SOAP Modernization | Wrap or migrate legacy SOAP/WSDL services to REST/JSON while maintaining backward compatibility. |
| Spring Boot Microservices | Use CXF Spring Boot starters to quickly expose JAX-RS or JAX-WS services in microservice architectures. |
| WS-Security Integration | Secure web services with SAML, Kerberos, PKI, or WS-Username Tokens using CXF WSS4J integration. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Framework | CXF provides deep Spring integration including Spring Boot starters for JAX-WS and JAX-RS. |
| Apache Karaf / OSGi | CXF runs as OSGi bundles in Apache Karaf for modular service deployment. |
| Apache Tomcat / Jetty | CXF services deploy as WAR files or embedded in Tomcat or Jetty servlet containers. |
| Apache WSS4J | CXF uses WSS4J for WS-Security implementation including XML Signature and SAML. |
| OpenAPI / Swagger | CXF integrates with Swagger/OpenAPI for automatic API documentation of JAX-RS services. |
| Apache Camel | CXF provides a Camel component for integrating web services into Camel routing and mediation flows. |

## Artifacts

Machine-readable schemas for Apache CXF endpoint and security configuration models.

### JSON Schema

- [Jaxrs Endpoint](json-schema/apache-cxf-jaxrs-endpoint-schema.json)
- [Jaxws Endpoint](json-schema/apache-cxf-jaxws-endpoint-schema.json)
- [Ws Security Config](json-schema/apache-cxf-ws-security-config-schema.json)

### JSON Structure

- [Jaxrs Endpoint](json-structure/apache-cxf-jaxrs-endpoint-structure.json)
- [Jaxws Endpoint](json-structure/apache-cxf-jaxws-endpoint-structure.json)
- [Ws Security Config](json-structure/apache-cxf-ws-security-config-structure.json)

### JSON-LD

- [Apache Cxf](json-ld/apache-cxf-context.jsonld)

### Examples

- [Jaxrs Endpoint](examples/apache-cxf-jaxrs-endpoint-example.json)
- [Jaxws Endpoint](examples/apache-cxf-jaxws-endpoint-example.json)
- [Ws Security Config](examples/apache-cxf-ws-security-config-example.json)

## Vocabulary

- [Apache CXF Vocabulary](vocabulary/apache-cxf-vocabulary.yaml) — Taxonomy mapping 5 resources, 4 actions, and 3 personas across JAX-WS and JAX-RS service development

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
