# Evidation Health

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
