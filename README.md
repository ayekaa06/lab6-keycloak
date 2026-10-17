# Lab 6 — Keycloak Identity and Access Management

## Objective
Configure Keycloak and verify a custom user attribute in an OpenID Connect ID token.

## Environment
- Keycloak
- OpenID Connect (OIDC)
- Local test application: OWASP Juice Shop

## Configuration
- Realm: lab 6
- Client: lab6-app
- Client scope: discipline
- User: student1
- Custom user attribute: discipline
- Attribute value: Cybersecurity
- Protocol mapper: discipline-mapper

## Verification
The generated ID token was checked successfully and contained:

    "discipline": "Cybersecurity"

## Evidence
Screenshots of the configuration and token verification will be added to the screenshots folder.

## Video Demonstration
A demonstration video will be added or linked here after recording.
