# Spring Security

Spring Security is a powerful and highly customizable authentication and access-control framework for Java applications. It is the de-facto standard for securing Spring-based applications, providing comprehensive security services including authentication, authorization, CSRF protection, OAuth 2.0, OpenID Connect, SAML 2.0, LDAP, and WebFlux reactive security.

**URL:** https://spring.io/projects/spring-security

## Tags

Authentication, Authorization, Java, JWT, OAuth2, OpenID Connect, SAML, Security, Spring Framework

## APIs

### Spring Security OAuth2 API

OAuth 2.0 and OpenID Connect support for Spring Security. Provides authorization code flow, token endpoint, token refresh, PKCE support, resource server JWT validation, and OIDC discovery.

**Human URL:** https://spring.io/projects/spring-security
**Base URL:** http://localhost:8080

**Tags:** Authorization Server, JWT, OAuth2, OpenID Connect, Token

**Properties:**
- [Documentation](https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html)
- [OAuth2 Client Documentation](https://docs.spring.io/spring-security/reference/servlet/oauth2/client/index.html)
- [OAuth2 Resource Server](https://docs.spring.io/spring-security/reference/servlet/oauth2/resource-server/index.html)
- [OpenAPI](openapi/spring-security-oauth2-openapi.yml)
- [JSON Schema](json-schema/spring-security-token-schema.json)
- [JSON Structure](json-structure/spring-security-token-structure.json)

### Spring Authorization Server API

Spring's implementation of an OAuth 2.1 and OpenID Connect 1.0 authorization server. Provides token issuance, introspection, PKCE, device authorization, and dynamic client registration.

**Human URL:** https://spring.io/projects/spring-authorization-server
**Base URL:** http://localhost:9000

**Tags:** Authorization Server, OAuth2, OpenID Connect, Token Issuance

**Properties:**
- [Documentation](https://docs.spring.io/spring-authorization-server/docs/current/reference/html/)
- [GitHub Repository](https://github.com/spring-projects/spring-authorization-server)
- [Getting Started](https://docs.spring.io/spring-authorization-server/docs/current/reference/html/getting-started.html)
- [OpenAPI](openapi/spring-authorization-server-openapi.yml)

### Spring Security Core

Core security features for authentication and authorization. Provides UserDetailsService, password encoding, security context management, method security, and HTTP security configuration.

**Human URL:** https://spring.io/projects/spring-security

**Tags:** Authentication, Authorization, Core, Method Security

**Properties:**
- [Documentation](https://docs.spring.io/spring-security/reference/)
- [API Reference](https://docs.spring.io/spring-security/site/docs/current/api/)
- [Getting Started](https://spring.io/guides/gs/securing-web/)
- [GitHub Repository](https://github.com/spring-projects/spring-security)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.security)

### Spring Security SAML2

SAML 2.0 Service Provider support enabling SSO integration with SAML identity providers, handling authentication requests, assertions, and Single Logout.

**Human URL:** https://docs.spring.io/spring-security/reference/servlet/saml2/index.html

**Tags:** Enterprise SSO, Federation, SAML, Single Logout

**Properties:**
- [Documentation](https://docs.spring.io/spring-security/reference/servlet/saml2/index.html)
- [SAML2 Login](https://docs.spring.io/spring-security/reference/servlet/saml2/login/index.html)
- [GitHub Repository](https://github.com/spring-projects/spring-security)

### Spring Security LDAP

LDAP authentication and authorization support. Supports LDAP bind authentication, password comparison, and user details loading from directory services.

**Human URL:** https://spring.io/projects/spring-security

**Tags:** Authentication, Directory Services, Enterprise, LDAP

**Properties:**
- [Documentation](https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/ldap.html)
- [Guide](https://spring.io/guides/gs/authenticating-ldap/)

### Spring Security WebFlux

Reactive security for Spring WebFlux applications. Provides non-blocking authentication, authorization, OAuth2 reactive client support, and CSRF protection.

**Human URL:** https://spring.io/projects/spring-security

**Tags:** Non-Blocking, Reactive, Security, WebFlux

**Properties:**
- [Documentation](https://docs.spring.io/spring-security/reference/reactive/index.html)
- [Getting Started](https://docs.spring.io/spring-security/reference/reactive/getting-started.html)
- [OAuth2 WebFlux](https://docs.spring.io/spring-security/reference/reactive/oauth2/index.html)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-security-oauth2-openapi.yml](openapi/spring-security-oauth2-openapi.yml) | Spring Security OAuth2 and OIDC protocol endpoints |
| [spring-authorization-server-openapi.yml](openapi/spring-authorization-server-openapi.yml) | Spring Authorization Server OAuth 2.1 endpoints |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-security-token-schema.json](json-schema/spring-security-token-schema.json) | OAuth2 token response, introspection, and error schemas |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-security-token-structure.json](json-structure/spring-security-token-structure.json) | Token response, JWT claims, and UserInfo structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-security-context.jsonld](json-ld/spring-security-context.jsonld) | Spring Security OAuth2 linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-security-issue-token-example.json](examples/spring-security-issue-token-example.json) | Issue OAuth2 token using client_credentials grant |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-security-rules.yml](rules/spring-security-rules.yml) | API design rules for Spring Security conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/identity-and-access.yaml](capabilities/identity-and-access.yaml) | Identity and access management workflow |
| [capabilities/shared/spring-security-oauth2.yaml](capabilities/shared/spring-security-oauth2.yaml) | Shared Spring Security OAuth2 consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-security-vocabulary.yml](vocabulary/spring-security-vocabulary.yml) | Spring Security domain vocabulary and terminology |

## Common Properties

- [Blog](https://spring.io/blog/category/security)
- [Community](https://stackoverflow.com/questions/tagged/spring-security)
- [Twitter](https://twitter.com/SpringSecurity)
- [Issue Tracker](https://github.com/spring-projects/spring-security/issues)
- [Contributing Guide](https://github.com/spring-projects/spring-security/blob/main/CONTRIBUTING.adoc)
- [License](https://github.com/spring-projects/spring-security/blob/main/LICENSE.txt)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.security)

## Maintainers

**Name:** Spring Security Team  
**Email:** spring-security@vmware.com  
**URL:** https://spring.io/team
