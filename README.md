# Liftoff

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

Liftoff (onliftoff.com, formerly liftoff.xyz) is a B2B network-based hiring and networking platform for startup leaders and hiring managers. Companies create a job search, attach a self-set "Match Incentive" referral bonus, and share the search link with their own network or with Liftoff's curated "Top Connectors" — senior leaders who refer pre-vetted candidates from their professional circles. Candidates surface through 2nd- and 3rd-degree trusted connections, and companies pay on a success-only basis, with fees due after a new hire completes 90 days.

Liftoff targets seed-to-Series-B technology companies, primarily in the New York City and San Francisco ecosystems, and positions itself between LinkedIn recruiting and traditional retained search.

Backed by: forerunner-ventures — https://www.onliftoff.com

## Not to be confused with

- **Liftoff Mobile** (liftoff.io) — mobile marketing / ad tech, unrelated.
- **useLiftoff** (useliftoff.com) — AI interview practice and job matching for job seekers, unrelated.

## API surface

Liftoff publishes **no public API**, SDK, developer portal, API documentation, or GitHub organization. There is no OpenAPI, AsyncAPI, webhook, or MCP surface to harvest, so the spec-bearing artifacts of the enrichment pipeline (openapi, overlays, errors, lifecycle, scopes, authentication, conventions, data-model, skills, arazzo, agentic-access, packages, cli, sandbox, components, changelog) are intentionally absent rather than fabricated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/liftoff-llms.txt` | searched (verbatim from https://www.onliftoff.com/llms.txt) |
| Domain security | `security/liftoff-domain-security.yml` | probed |
| Well-Known index | `well-known/liftoff-well-known.yml` | searched (no documents found) |
