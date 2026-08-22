# Spring Security (spring-security)

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
