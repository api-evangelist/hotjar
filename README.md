# hotjar (hotjar)

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

Hotjar is a behavior analytics and user feedback platform that helps businesses understand how users interact with their website through heatmaps, session recordings, surveys, and feedback widgets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Hotjar REST API

The Hotjar REST API provides programmatic access to Hotjar data and functionality. It allows developers to export survey responses, automate user lookup and deletion requests, and integrate Hotjar data into external tools and workflows. The API uses OAuth client credentials authentication, returns JSON responses, supports cursor-based pagination, and is rate limited to 3000 requests per minute. It is available on Observe and Ask Scale plans.

- **Human URL:** [https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference](https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference)
- **Base URL:** `https://api.hotjar.com`

#### Tags

- Analytics
- Behavior
- Heatmaps
- Surveys
- User Feedback

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference)
- [OpenAPI](openapi/hotjar-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hotjar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotjar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hotjar Events API

The Hotjar Events API is a client-side JavaScript API that allows developers to send custom events to Hotjar when specific actions take place on a website. These events can be used to filter collected Recordings and Heatmap data, trigger session capture, and target Surveys to appear based on user behavior. Events are sent using the Hotjar tracking code and are available on all pages where the tracking snippet is installed.

- **Human URL:** [https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference](https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Events
- Heatmaps
- Recordings
- Surveys
- Tracking

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference)
- [Postman Collection](collections/hotjar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotjar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hotjar Identify API

The Hotjar Identify API is a client-side JavaScript API that allows developers to pass user data to Hotjar, saving it as User Attributes. These attributes enable advanced filtering and segmentation of Hotjar data such as Recordings, Heatmaps, and Surveys. The Identify API must be called before the Events API in the execution order. It is used via the Hotjar tracking code on pages where the JavaScript snippet is installed.

- **Human URL:** [https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference](https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Attributes
- Personalization
- Segmentation
- Users

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference)
- [Postman Collection](collections/hotjar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotjar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hotjar JavaScript SDK

The Hotjar JavaScript SDK (@hotjar/browser) is an npm package that provides a programmatic interface for integrating Hotjar directly into JavaScript applications. It allows developers to initialize Hotjar with a site ID, identify users, and send custom events without manually embedding the tracking script. The SDK supports modern JavaScript frameworks including React, Vue, and Angular, and provides methods for all Hotjar client-side APIs including identify and event tracking.

- **Human URL:** [https://github.com/hotjar/hotjar-js](https://github.com/hotjar/hotjar-js)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Browser
- JavaScript
- SDK
- Tracking

#### Properties

- [Documentation](https://github.com/hotjar/hotjar-js)
- [Postman Collection](collections/hotjar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hotjar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hotjar)
- [JSON-LD](json-ld/hotjar-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/hotjar-survey-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotjar-survey-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hotjar-user-lookup-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
