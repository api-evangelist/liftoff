# Liftoff

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
