# CodeSandbox (codesandbox)

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

CodeSandbox is a browser-based development environment platform that enables developers to create, share, and collaborate on interactive coding sandboxes instantly in the browser. It provides Firecracker microVM-backed cloud infrastructure for running isolated development environments, AI sandboxes, and live code experiences at scale. The platform serves individual developers, professional teams, and AI product builders needing concurrent sandboxed environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/codesandbox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/codesandbox/refs/heads/main/apis.yml)

**Naftiko Run:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=codesandbox-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=codesandbox-api-evangelist&utm_content=repo)

## Tags

- Developer Tools
- Cloud IDE
- Code Sandboxes
- Browser Development
- AI Sandboxes
- Code Embedding
- Virtual Machines

## APIs

- **CodeSandbox SDK API** — Programmatic access to spin up isolated Firecracker microVM-backed development environments; authenticated via API key token.
  - Docs: [https://codesandbox.io/docs/sdk](https://codesandbox.io/docs/sdk)
  - GitHub: [https://github.com/codesandbox/codesandbox-sdk](https://github.com/codesandbox/codesandbox-sdk)

- **CodeSandbox Define API** — REST API for programmatically creating browser sandboxes from code files on the fly.
  - Docs: [https://codesandbox.io/docs/learn/browser-sandboxes/cli-api](https://codesandbox.io/docs/learn/browser-sandboxes/cli-api)
  - Endpoint: `POST https://codesandbox.io/api/v1/sandboxes/define`

- **Sandpack Embed Toolkit** — Open-source component toolkit for embedding live-running code editors and previews in web pages.
  - Docs: [https://sandpack.codesandbox.io/docs](https://sandpack.codesandbox.io/docs)
  - GitHub: [https://github.com/codesandbox/sandpack](https://github.com/codesandbox/sandpack)

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/codesandbox-plans-pricing.yml) — Free (400 credits/month), Build ($9/mo, 40 VM hours), Scale ($119/mo, 100 VM hours, 250 concurrent VMs), Enterprise (custom)
- [Rate Limits](rate-limits/codesandbox-rate-limits.yml) — Concurrent VM caps: 10 (Free/Build), 250 (Scale); billing rounds up to nearest minute
- [FinOps](finops/codesandbox-finops.yml) — FOCUS-aligned; credits at $0.01486/credit, on-demand VM at $0.15/hour (Nano)

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://codesandbox.io](https://codesandbox.io) |
| Documentation | [https://codesandbox.io/docs/learn](https://codesandbox.io/docs/learn) |
| GitHub Organization | [https://github.com/codesandbox](https://github.com/codesandbox) |
| LinkedIn | [https://www.linkedin.com/company/codesandbox](https://www.linkedin.com/company/codesandbox) |
| X (Twitter) | [https://x.com/codesandbox](https://x.com/codesandbox) |
| Blog | [https://codesandbox.io/blog](https://codesandbox.io/blog) |
| Changelog | [https://codesandbox.io/changelog](https://codesandbox.io/changelog) |
| Pricing | [https://codesandbox.io/pricing](https://codesandbox.io/pricing) |
| Status Page | [https://status.codesandbox.io](https://status.codesandbox.io) |

## Maintainers

- **Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
