# Kagi (kagi)

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

Kagi is a privacy-focused premium search engine that also operates a commercial APIs portfolio for developers. The Kagi APIs Portal exposes Search, Enrichment, Universal Summarizer, and FastGPT endpoints, plus a free Small Web RSS feed for non-commercial use. The portal includes an API Playground, usage dashboard, and API key management with IP allowlists and per-product scopes. Kagi publishes an OpenAPI specification and ships official client libraries in Python, Go, Rust, and TypeScript. Billing is pay-per-use with monthly invoicing and a Discord community for developer support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kagi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kagi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Search
- Premium Search
- AI Search
- Summarization
- FastGPT
- Enrichment
- OpenAPI
- Pay-Per-Use
- Privacy
- LLMs
- Web Index

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Kagi Search API

The Kagi Search API delivers premium, ad-free web search results powered by the Kagi index, designed for AI agents, research workflows, and applications that demand high-quality results.

- **Human URL:** [https://help.kagi.com/kagi/api/search.html](https://help.kagi.com/kagi/api/search.html)
- **Base URL:** `https://kagi.com/api/v0`

#### Tags

- Search
- Web
- REST

#### Properties

- [Documentation](https://help.kagi.com/kagi/api/search.html)
- [Getting Started](https://help.kagi.com/kagi/api/intro.html)
- [Sign Up](https://kagi.com/signup)
- [API Reference](https://help.kagi.com/kagi/api/search.html)
- [SDK](https://github.com/kagisearch)
- [Pricing](https://help.kagi.com/kagi/api/overview.html)
- [Authentication](https://help.kagi.com/kagi/api/intro.html)
- [Postman Collection](collections/kagi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kagi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kagi Enrichment API

The Kagi Enrichment API provides access to Kagi's Teclis non-commercial web index and TinyGem news index for specialized retrieval and discovery workloads.

- **Human URL:** [https://help.kagi.com/kagi/api/enrich.html](https://help.kagi.com/kagi/api/enrich.html)
- **Base URL:** `https://kagi.com/api/v0`

#### Tags

- Enrichment
- Teclis
- TinyGem
- News
- Web Index

#### Properties

- [Documentation](https://help.kagi.com/kagi/api/enrich.html)
- [API Reference](https://help.kagi.com/kagi/api/enrich.html)
- [Pricing](https://help.kagi.com/kagi/api/overview.html)
- [Postman Collection](collections/kagi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kagi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kagi Universal Summarizer API

The Universal Summarizer API condenses URLs, documents, audio, and video into structured summaries using Kagi's hosted models.

- **Human URL:** [https://help.kagi.com/kagi/api/summarizer.html](https://help.kagi.com/kagi/api/summarizer.html)
- **Base URL:** `https://kagi.com/api/v0`

#### Tags

- Summarization
- Documents
- Audio
- Video
- LLMs

#### Properties

- [Documentation](https://help.kagi.com/kagi/api/summarizer.html)
- [API Reference](https://help.kagi.com/kagi/api/summarizer.html)
- [Pricing](https://help.kagi.com/kagi/api/overview.html)
- [Postman Collection](collections/kagi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kagi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kagi FastGPT API

FastGPT is Kagi's LLM-powered question answering API that combines a hosted model with live Kagi web search for grounded, cited answers.

- **Human URL:** [https://help.kagi.com/kagi/api/fastgpt.html](https://help.kagi.com/kagi/api/fastgpt.html)
- **Base URL:** `https://kagi.com/api/v0`

#### Tags

- FastGPT
- QA
- Grounded Answers
- LLMs
- Search

#### Properties

- [Documentation](https://help.kagi.com/kagi/api/fastgpt.html)
- [API Reference](https://help.kagi.com/kagi/api/fastgpt.html)
- [Pricing](https://help.kagi.com/kagi/api/overview.html)
- [Postman Collection](collections/kagi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kagi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://kagi.com)
- [Documentation](https://help.kagi.com/kagi/api/overview.html)
- [Blog](https://blog.kagi.com)
- [GitHub Organization](https://github.com/kagisearch)
- [Pricing](https://help.kagi.com/kagi/api/overview.html)
- [Terms of Service](https://kagi.com/terms)
- [Privacy Policy](https://kagi.com/privacy)
- [Discord](https://kagi.com/discord)
- [X (Twitter)](https://x.com/kagihq)
- [Changelog](https://kagi.com/changelog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
