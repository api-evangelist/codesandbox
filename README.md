# CodeSandbox (codesandbox)

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
