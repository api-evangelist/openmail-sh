# openmail-sh

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

Openmail.sh is a developer-focused email service platform that provides programmable email sending, inbound routing, and webhook notifications. It enables applications to integrate email capabilities via simple RESTful APIs, offering features such as template management, analytics, and domain authentication. The service targets SaaS developers, marketers, and enterprises seeking to automate transactional and marketing communications while maintaining deliverability and compliance.

**Areas:** Company · Email · API · AI · Developer

## openmail-sh on APIs.io

Everything profiled for openmail-sh is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/openmail-sh/](https://apis.io/providers/openmail-sh/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [openmail-sh Attachments API](https://apis.io/apis/openmail-sh/openmail-sh-attachments-api/) — Downloading and extracting text from attachments
- [openmail-sh Domains API](https://apis.io/apis/openmail-sh/openmail-sh-domains-api/) — Custom domains: add your own sending/receiving domain, publish DNS, and verify it
- [openmail-sh Feedback API](https://apis.io/apis/openmail-sh/openmail-sh-feedback-api/) — Reporting bugs, friction, and feature requests to the OpenMail team
- [openmail-sh Inboxes API](https://apis.io/apis/openmail-sh/openmail-sh-inboxes-api/) — Email inboxes and their webhook configuration
- [openmail-sh Limits API](https://apis.io/apis/openmail-sh/openmail-sh-limits-api/) — Sending limits: today's cold outreach caps on new recipients, per account, inbox, and domain, and what raises them
- [openmail-sh Messages API](https://apis.io/apis/openmail-sh/openmail-sh-messages-api/) — Sending and listing messages
- [openmail-sh Owned Domains API](https://apis.io/apis/openmail-sh/openmail-sh-owned-domains-api/) — Domains your organisation controls but does not send from. Prove ownership with one TXT record and mail to their addresses stops counting toward the cold…
- [openmail-sh Pods API](https://apis.io/apis/openmail-sh/openmail-sh-pods-api/) — Isolated sub-accounts for your end users or tenants
- [openmail-sh Policy API](https://apis.io/apis/openmail-sh/openmail-sh-policy-api/) — Correspondent policy — provider-enforced allow/block rules and allowlist mode, scoped per account, pod, or inbox. Account-wide key only.
- [openmail-sh Threads API](https://apis.io/apis/openmail-sh/openmail-sh-threads-api/) — Conversation threads and read status

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Openmail Sh Webhooks](https://apis.io/asyncapis/openmail-sh/openmail-sh-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Openmail Sh Agentic Access](https://apis.io/agentic-access/openmail-sh/openmail-sh-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ApiKey](https://apis.io/schemas/openmail-sh/openmail-sh-api-key/)
- [ColdCapLimits](https://apis.io/schemas/openmail-sh/openmail-sh-cold-cap-limits/)
- [Domain](https://apis.io/schemas/openmail-sh/openmail-sh-domain/)
- [Inbox](https://apis.io/schemas/openmail-sh/openmail-sh-inbox/)
- [Message](https://apis.io/schemas/openmail-sh/openmail-sh-message/)
- [OwnedDomain](https://apis.io/schemas/openmail-sh/openmail-sh-owned-domain/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Openmail Sh Context](https://apis.io/jsonld/openmail-sh/openmail-sh-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [openmail-sh API Rules](https://apis.io/rules/openmail-sh/openmail-sh-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Openmail Sh Authentication](https://apis.io/security/openmail-sh/openmail-sh-authentication/)
- [Openmail Sh Domain Security](https://apis.io/security/openmail-sh/openmail-sh-domain-security/)
- [Openmail Sh Vulnerability Disclosure](https://apis.io/security/openmail-sh/openmail-sh-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Openmail Sh Plans Pricing](https://apis.io/plans/openmail-sh/openmail-sh-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Openmail Sh Rate Limits](https://apis.io/rate-limits/openmail-sh/openmail-sh-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://openmail.sh/)
- [Documentation](https://docs.openmail.sh/)
- [Getting started](https://docs.openmail.sh/quickstart)
- [API reference](https://docs.openmail.sh/api-reference/introduction)
- [Pricing](https://openmail.sh/pricing)
- [Sign up](https://console.openmail.sh/signup)
- [Blog](https://openmail.sh/blog/)
- [Security](https://openmail.sh/terms)
- [Terms of service](https://openmail.sh/terms)
- [Privacy policy](https://openmail.sh/privacy)
- [GitHub](https://github.com/openmailsh)
- [Status](https://status.openmail.sh)

## API Evangelist rating

**Kin Score 70.4** — exemplar · rubric 0.25.0 · scored 2026-10-31

| Facet | Score |
|---|---|
| Discoverability | 67.9 |
| Contract quality | 65.8 |
| Contract governance | 70.9 |
| Operational transparency | 67.9 |
| Developer ergonomics | 66.0 |
| Access clarity | 73.2 |

**Agent readiness 69.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 28.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/openmail-sh/](https://apis.io/providers/openmail-sh/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for openmail-sh: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/openmail-sh/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
