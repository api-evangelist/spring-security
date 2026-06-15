# Spring Security (spring-security)

Spring Security is a powerful and highly customizable authentication and access-control framework for Java applications. It is the de-facto standard for securing Spring-based applications, providing comprehensive security services including authentication, authorization, protection against common exploits (CSRF, session fixation, clickjacking), OAuth 2.0, OpenID Connect, SAML 2.0, LDAP, and WebFlux reactive security.

**APIs.json:** [https://spring.io/projects/spring-security](https://spring.io/projects/spring-security)

## Scope

- **Type:** Index

## Tags

- Authentication
- Authorization
- Java
- JWT
- OAuth2
- OpenID Connect
- SAML
- Security
- Spring Framework

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Spring Security OAuth2 API

OAuth 2.0 and OpenID Connect support for Spring Security. Provides client registration, authorization code flow, token endpoint, token refresh, PKCE support, and resource server JWT validation.

- **Human URL:** [https://spring.io/projects/spring-security](https://spring.io/projects/spring-security)
- **Base URL:** `http://localhost:8080`

#### Tags

- Authorization Server
- JWT
- OAuth2
- OpenID Connect
- Token

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html)
- [O Auth2  Client  Documentation](https://docs.spring.io/spring-security/reference/servlet/oauth2/client/index.html)
- [O Auth2  Resource  Server](https://docs.spring.io/spring-security/reference/servlet/oauth2/resource-server/index.html)
- [Authorization  Server](https://spring.io/projects/spring-authorization-server)
- [OpenAPI](openapi/spring-security-oauth2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-security-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-security-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Authorization Server API

Spring's implementation of an OAuth 2.1 and OpenID Connect 1.0 authorization server. Provides issuing access tokens, refresh tokens, and ID tokens with support for PKCE, token introspection, and authorization server metadata.

- **Human URL:** [https://spring.io/projects/spring-authorization-server](https://spring.io/projects/spring-authorization-server)
- **Base URL:** `http://localhost:9000`

#### Tags

- Authorization Server
- OAuth2
- OpenID Connect
- Token Issuance

#### Properties

- [Documentation](https://docs.spring.io/spring-authorization-server/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-authorization-server)
- [Getting Started](https://docs.spring.io/spring-authorization-server/docs/current/reference/html/getting-started.html)
- [OpenAPI](openapi/spring-authorization-server-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-authorization-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-authorization-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Security Core

Core security features for authentication and authorization. Provides UserDetailsService, password encoding, security context management, method security, and HTTP security configuration.

- **Human URL:** [https://spring.io/projects/spring-security](https://spring.io/projects/spring-security)
- **Base URL:** `https://docs.spring.io/spring-security/site/docs/current/api/`

#### Tags

- Authentication
- Authorization
- Core
- Method Security

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/)
- [API Reference](https://docs.spring.io/spring-security/site/docs/current/api/)
- [Getting Started](https://spring.io/guides/gs/securing-web/)
- [GitHub Repository](https://github.com/spring-projects/spring-security)
- [Release Notes](https://github.com/spring-projects/spring-security/releases)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.security)
- [Postman Collection](collections/spring-authorization-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-authorization-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-security-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-security-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Security SAML2

SAML 2.0 Service Provider support for Spring Security. Enables SSO integration with SAML identity providers, handling authentication requests, assertions, and SLO (Single Logout).

- **Human URL:** [https://docs.spring.io/spring-security/reference/servlet/saml2/index.html](https://docs.spring.io/spring-security/reference/servlet/saml2/index.html)

#### Tags

- Enterprise SSO
- Federation
- SAML
- Single Logout

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/servlet/saml2/index.html)
- [S A M L2  Login](https://docs.spring.io/spring-security/reference/servlet/saml2/login/index.html)
- [GitHub Repository](https://github.com/spring-projects/spring-security)
- [Postman Collection](collections/spring-authorization-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-authorization-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-security-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-security-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Security LDAP

LDAP authentication and authorization support for Spring Security. Supports LDAP bind authentication, password comparison, and user details loading from directory services.

- **Human URL:** [https://spring.io/projects/spring-security](https://spring.io/projects/spring-security)

#### Tags

- Authentication
- Directory Services
- Enterprise
- LDAP

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/ldap.html)
- [Guide](https://spring.io/guides/gs/authenticating-ldap/)
- [Postman Collection](collections/spring-authorization-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-authorization-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-security-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-security-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Security WebFlux

Reactive security for Spring WebFlux applications. Provides non-blocking authentication, authorization, OAuth2 reactive client support, and CSRF protection for reactive web stacks.

- **Human URL:** [https://spring.io/projects/spring-security](https://spring.io/projects/spring-security)

#### Tags

- Non-Blocking
- Reactive
- Security
- WebFlux

#### Properties

- [Documentation](https://docs.spring.io/spring-security/reference/reactive/index.html)
- [Getting Started](https://docs.spring.io/spring-security/reference/reactive/getting-started.html)
- [O Auth2  Web Flux](https://docs.spring.io/spring-security/reference/reactive/oauth2/index.html)
- [Postman Collection](collections/spring-authorization-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-authorization-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-security-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-security-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Blog](https://spring.io/blog/category/security)
- [Community](https://stackoverflow.com/questions/tagged/spring-security)
- [Twitter](https://twitter.com/SpringSecurity)
- [Issue  Tracker](https://github.com/spring-projects/spring-security/issues)
- [Contributing  Guide](https://github.com/spring-projects/spring-security/blob/main/CONTRIBUTING.adoc)
- [License](https://github.com/spring-projects/spring-security/blob/main/LICENSE.txt)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.security)
- [Changelog](https://github.com/spring-projects/spring-security/releases)

## Maintainers

**FN:** Spring Security Team
**Email:** spring-security@vmware.com
**URL:** https://spring.io/team
