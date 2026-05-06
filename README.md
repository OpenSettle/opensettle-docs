# opensettle-docs

Public docs source for [OpenSettle](https://opensettle.io). The rendered
site lives at [opensettle.io/docs](https://opensettle.io/docs); this repo
holds the underlying source so:

- developers can grep and pin specific revisions
- pull requests for typos and clarifications can land here
- search engines and downstream tools can crawl the canonical text
- mirrors and translations have a stable upstream

## What's documented

| Topic | Lives at |
|---|---|
| Getting started | [opensettle.io/docs](https://opensettle.io/docs) |
| 5-minute quickstart | [opensettle.io/docs/quickstart](https://opensettle.io/docs/quickstart) |
| API reference | [opensettle.io/docs/api](https://opensettle.io/docs/api) |
| Live API explorer | [api.opensettle.io/v1/docs](https://api.opensettle.io/v1/docs) |
| OpenAPI spec | [api.opensettle.io/v1/openapi.json](https://api.opensettle.io/v1/openapi.json) · [github.com/OpenSettle/opensettle-openapi](https://github.com/OpenSettle/opensettle-openapi) |
| SDK reference | [opensettle.io/docs/sdks](https://opensettle.io/docs/sdks) |
| Webhooks | [opensettle.io/docs/webhooks](https://opensettle.io/docs/webhooks) |
| Subscriptions | [opensettle.io/docs/subscriptions](https://opensettle.io/docs/subscriptions) |
| Refunds | [opensettle.io/docs/refunds](https://opensettle.io/docs/refunds) |
| Reconciliation | [opensettle.io/docs/reconciliation](https://opensettle.io/docs/reconciliation) |
| Security posture | [opensettle.io/docs/security](https://opensettle.io/docs/security) |
| Errors | [opensettle.io/docs/errors](https://opensettle.io/docs/errors) |
| Chains | [opensettle.io/docs/chains](https://opensettle.io/docs/chains) |
| CLI | [opensettle.io/docs/cli](https://opensettle.io/docs/cli) |

## Repo status

The docs source is currently authored in the OpenSettle web application
codebase (private). This repository will track Markdown exports of every
docs page so the canonical text is publicly browsable and pull-requestable.
The migration is in flight; until it lands, the live site is the
authoritative source.

## Contributing

Typos, clarifications, broken links, missing examples — all welcome.
Open a pull request with the change; reviews aim for same-week turnaround
once external traffic ramps up.

For substantive doc additions or restructures, please open an issue first
to align on shape before writing.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — copy, share,
remix with attribution.

## Security disclosures

Doc bugs are fine to file as public issues. **Security vulnerabilities in
the OpenSettle platform itself** should not be filed publicly — see
[security.txt](https://opensettle.io/.well-known/security.txt) or email
[opensettle@proton.me](mailto:opensettle@proton.me). Disclosure policy at
[opensettle.io/security](https://opensettle.io/security).
