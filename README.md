# hotjar (hotjar)

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
