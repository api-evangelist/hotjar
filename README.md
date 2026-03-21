# Hotjar (hotjar)
Hotjar is a behavior analytics and user feedback platform that helps businesses understand how users interact with their websites. Their developer platform provides REST APIs for exporting survey data and managing user records, as well as client-side JavaScript APIs for sending custom events, identifying users, and integrating tracking into modern web applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Analytics, Heatmaps, Surveys, User Feedback, Behavior, Tracking

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Hotjar REST API
The Hotjar REST API provides programmatic access to Hotjar data and functionality. It allows developers to export survey responses, automate user lookup and deletion requests, and integrate Hotjar data into external tools and workflows. The API uses OAuth client credentials authentication, returns JSON responses, supports cursor-based pagination, and is rate limited to 3000 requests per minute. It is available on Observe and Ask Scale plans.

**Human URL:** [https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference](https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference)


#### Tags:

 - Analytics, Surveys, Heatmaps, Behavior, User Feedback

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference)
- [OpenAPI](openapi/hotjar-rest-api-openapi.yml)

### Hotjar Events API
The Hotjar Events API is a client-side JavaScript API that allows developers to send custom events to Hotjar when specific actions take place on a website. These events can be used to filter collected Recordings and Heatmap data, trigger session capture, and target Surveys to appear based on user behavior. Events are sent using the Hotjar tracking code and are available on all pages where the tracking snippet is installed.

**Human URL:** [https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference](https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference)


#### Tags:

 - Events, Tracking, Heatmaps, Recordings, Surveys, Analytics

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference)

### Hotjar Identify API
The Hotjar Identify API is a client-side JavaScript API that allows developers to pass user data to Hotjar, saving it as User Attributes. These attributes enable advanced filtering and segmentation of Hotjar data such as Recordings, Heatmaps, and Surveys. The Identify API must be called before the Events API in the execution order. It is used via the Hotjar tracking code on pages where the JavaScript snippet is installed.

**Human URL:** [https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference](https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference)


#### Tags:

 - Users, Attributes, Segmentation, Analytics, Personalization

#### Properties

- [Documentation](https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference)

### Hotjar JavaScript SDK
The Hotjar JavaScript SDK (@hotjar/browser) is an npm package that provides a programmatic interface for integrating Hotjar directly into JavaScript applications. It allows developers to initialize Hotjar with a site ID, identify users, and send custom events without manually embedding the tracking script. The SDK supports modern JavaScript frameworks including React, Vue, and Angular, and provides methods for all Hotjar client-side APIs including identify and event tracking.

**Human URL:** [https://github.com/hotjar/hotjar-js](https://github.com/hotjar/hotjar-js)


#### Tags:

 - JavaScript, SDK, Analytics, Tracking, Browser

#### Properties

- [Documentation](https://github.com/hotjar/hotjar-js)

## Common Properties

- [Portal](https://help.hotjar.com/hc/en-us/categories/36819892654225-For-Developers)
- [Documentation](https://help.hotjar.com/hc/en-us)
- [Website](https://www.hotjar.com/)
- [PrivacyPolicy](https://www.hotjar.com/privacy/)
- [TermsOfService](https://www.hotjar.com/terms/)
- [Support](https://help.hotjar.com/hc/en-us)
- [Blog](https://www.hotjar.com/blog/)
- [Login](https://insights.hotjar.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
