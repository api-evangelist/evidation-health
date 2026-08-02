# Evidation Health

Evidation Health is a San Mateo, California digital health company, founded in 2012, that measures health in everyday life and runs permissioned real-world data research at scale. Its consumer app and platform — Achievement — rewards members for connecting wearables, apps and health records, and its enterprise Research & Engagement Platform gives life-sciences, payer, government and non-profit customers eConsent and onboarding, ePRO and survey capture, passive and active device monitoring, program analytics, and participant education.

Evidation combines permissioned data from sources including Apple Health, Fitbit, Garmin, Dexcom and EHR/claims records (via partnerships with 1upHealth's FHIR-based Patient Connect and with HealthVerity), and has enabled 175+ virtual real-world studies and 70+ peer-reviewed publications.

## API surface

As of 2026-08-01 Evidation publishes **no public developer program, API documentation, or machine-readable API contract**. Probes of every Evidation host found no OpenAPI/Swagger, no GraphQL, no AsyncAPI, no MCP server and no A2A agent card. `api.us.evidation.com` is the member application backend and app-store deep-link host — a single-page-app catch-all that answers HTTP 200 with the same HTML shell for every path, so it yields no discoverable contract. Integration with Evidation is a commercial arrangement, not a self-serve developer signup.

## What was found

- [security.txt](https://evidation.com/.well-known/security.txt) (RFC 9116) — vulnerability contact `vuln@evidation.com`, PGP fingerprint, expires 2027-08-21. The privacy notice also lists `security@evidation.com`.
- Domain security: TLS 1.3, HSTS (max-age 15552000), DNSSEC enabled, SPF and DMARC with `p=reject`, no CAA record.
- [GitHub organization](https://github.com/evidation-health) exists with zero public repositories.
- No status page, no changelog, no SDKs or packages in any public registry, no Postman workspace, no published compliance certifications (SOC 2 / ISO 27001 / HITRUST are not claimed on the public site).

## Links

- Website — https://evidation.com/
- Platform — https://evidation.com/for-customers/our-platform
- Blog — https://evidation.com/blog
- Newsroom — https://evidation.com/newsroom
- Help center — https://help.evidation.com/hc/en-us
- Join research — https://evidation.com/join-research
- Member sign in — https://my.evidation.com/
- Terms — https://evidation.com/terms
- Privacy — https://evidation.com/privacy
