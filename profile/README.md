<h1 align="left">SendBeam</h1>

<p align="left"><strong>One email account for every site you run.</strong></p>

Most email platforms are built for one brand with one list. If you run several small sites — a calculator, a
directory, a couple of side projects, a handful of client brands — you end up with a separate account, a
separate bill and a separate sending domain for each one, and a contact form bolted on from somewhere else.

SendBeam is one account holding a workspace per site. Contacts and sending allowance are pooled across the
account, each site keeps its own sending domain, forms and lists, and the whole thing is one bill.

[**sendbeam.io**](https://sendbeam.io) · [Docs](https://sendbeam.io/docs) · [Pricing](https://sendbeam.io/pricing) · [Changelog](https://sendbeam.io/changelog) · [Status](https://sendbeam.io/api/health)

## What it does

- **Forms without a backend.** Signup and contact forms that post straight from a static site, with double
  opt-in, owner notifications, an origin allow-list, rate limits and optional Turnstile.
- **Newsletters and automations.** Campaigns, segments, tags and automations, with audience counts that match
  what actually gets sent.
- **Transactional email** over a REST API, with an [OpenAPI spec](https://sendbeam.io/openapi.json).
- **Sending domains** you own, with the DNS records written for you on Cloudflare, and the headers Gmail,
  Yahoo and Microsoft now require set for you.
- **Move-in.** We migrate your lists, suppressions, tags and consent evidence from another platform, free on
  the paid plans.

## Repositories here

| Repo | What it is |
| --- | --- |
| [**sendbeam-starters**](https://github.com/sendbeam-io/sendbeam-starters) | Five runnable starters — plain HTML, Astro, Eleventy, Next.js and Hugo — showing newsletter signup and contact forms with no backend of your own. MIT. |

Most of SendBeam is a closed-source product. What lives here is the part meant to be copied: working code you
can lift into your own site.

## Free tools

- [**Sender check**](https://sendbeam.io/tools/sender-check) — enter a domain and see whether it meets the
  Gmail, Yahoo and Microsoft bulk-sender rules: SPF, DKIM, DMARC alignment, reverse DNS, and the one-click
  unsubscribe headers most checkers ignore. No account needed.
- [**Cost calculator**](https://sendbeam.io/tools/cost-calculator) — what several sites actually cost on the
  platforms that bill you per list.

## Getting help

- Product questions: [sendbeam.io/contact](https://sendbeam.io/contact)
- Something wrong with the starters: [open an issue](https://github.com/sendbeam-io/sendbeam-starters/issues)
- Security: see the [security policy](https://github.com/sendbeam-io/sendbeam-starters/blob/main/SECURITY.md)
  and email hello@sendbeam.io rather than filing publicly

Built and run in the UK.
