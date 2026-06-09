# opensettle-docs

Public mirror of the [OpenSettle](https://opensettle.io) documentation
hosted at [opensettle.io/docs](https://opensettle.io/docs).

> **Status: this repo is a pointer, not a source.** The docs are authored
> inside the (private) OpenSettle web app codebase. The live site at
> [opensettle.io/docs](https://opensettle.io/docs) is the authoritative
> source. The page index below is current.
>
> **Need plain Markdown?** Every page under `/docs/*` is served as
> tokens-efficient Markdown by appending `.md` to the URL — e.g.
> [opensettle.io/docs/quickstart.md](https://opensettle.io/docs/quickstart.md).
> HTML responses also advertise the alternate via
> `Link: <…md>; rel="alternate"; type="text/markdown"`. Use that for
> LLM grounding, offline reading, and `curl`-friendly diffs.
>
> This repo exists so that:
>
> - typos and clarifications can be proposed as PRs (we hand-port
>   accepted ones into the web codebase)
> - issues for doc bugs have a public home separate from the
>   product issue tracker
> - the documentation surface has a discoverable presence on GitHub

## What's documented

| Topic | Lives at |
|---|---|
| Getting started | [opensettle.io/docs](https://opensettle.io/docs) |
| 5-minute quickstart | [opensettle.io/docs/quickstart](https://opensettle.io/docs/quickstart) |
| Core concepts | [opensettle.io/docs/concepts](https://opensettle.io/docs/concepts) |
| API reference | [opensettle.io/docs/api](https://opensettle.io/docs/api) |
| Live API explorer | [api.opensettle.io/v1/docs](https://api.opensettle.io/v1/docs) |
| OpenAPI spec | [api.opensettle.io/v1/openapi.json](https://api.opensettle.io/v1/openapi.json) · [github.com/OpenSettle/opensettle-openapi](https://github.com/OpenSettle/opensettle-openapi) |
| SDK reference | [opensettle.io/docs/sdks](https://opensettle.io/docs/sdks) |
| Checkouts | [opensettle.io/docs/checkouts](https://opensettle.io/docs/checkouts) |
| Invoices | [opensettle.io/docs/invoices](https://opensettle.io/docs/invoices) |
| Subscriptions | [opensettle.io/docs/subscriptions](https://opensettle.io/docs/subscriptions) |
| Refunds | [opensettle.io/docs/refunds](https://opensettle.io/docs/refunds) |
| Webhooks | [opensettle.io/docs/webhooks](https://opensettle.io/docs/webhooks) |
| Reconciliation | [opensettle.io/docs/reconciliation](https://opensettle.io/docs/reconciliation) |
| Errors | [opensettle.io/docs/errors](https://opensettle.io/docs/errors) |
| Chains (Base, Ethereum, Polygon, Arbitrum, Tron, Solana) | [opensettle.io/docs/chains](https://opensettle.io/docs/chains) |
| Wallet compatibility | [opensettle.io/docs/wallets](https://opensettle.io/docs/wallets) |
| Security posture | [opensettle.io/docs/security](https://opensettle.io/docs/security) |
| CLI | [opensettle.io/docs/cli](https://opensettle.io/docs/cli) |

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
[security@opensettle.io](mailto:security@opensettle.io). Disclosure policy at
[opensettle.io/security](https://opensettle.io/security).
