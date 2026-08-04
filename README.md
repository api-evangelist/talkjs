# TalkJS (talkjs)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

TalkJS is a chat API and SDK for adding messaging to web and mobile apps. It pairs a customizable pre-built chat UI (the TalkJS JavaScript SDK and Chat UI) with a server-side REST API at https://api.talkjs.com/v1/{appId} for managing users, conversations, participants, and messages, importing existing chat history, and receiving events via webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/talkjs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/talkjs/refs/heads/main/apis.yml)

## Tags

- Chat
- Messaging
- Communication
- SDK
- Webhooks

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### TalkJS Users API

Create, update, and retrieve TalkJS users, list users and a user's conversations, and manage per-user presence. Users are timeless resources upserted with PUT and updated PATCH-style with a subset of fields.

- **Human URL:** [https://talkjs.com/docs/Reference/REST_API/Users/](https://talkjs.com/docs/Reference/REST_API/Users/)
- **Base URL:** `https://api.talkjs.com/v1/{appId}`

#### Tags

- Users
- Presence
- Profiles

#### Properties

- [Documentation](https://talkjs.com/docs/Reference/REST_API/Users/)
- [API Reference](https://talkjs.com/docs/Reference/REST_API/Users/)
- [OpenAPI](openapi/talkjs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/talkjs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/talkjs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TalkJS Conversations & Participants API

Create, update, list, and delete conversations, and manage their participants — join (PUT), leave (DELETE), and set access (ReadWrite/Read) and notification preferences. Includes marking conversations read/unread per user.

- **Human URL:** [https://talkjs.com/docs/Reference/REST_API/Conversations/](https://talkjs.com/docs/Reference/REST_API/Conversations/)
- **Base URL:** `https://api.talkjs.com/v1/{appId}`

#### Tags

- Conversations
- Participants
- Access

#### Properties

- [Documentation](https://talkjs.com/docs/Reference/REST_API/Conversations/)
- [API Reference](https://talkjs.com/docs/Reference/REST_API/Conversations/)
- [OpenAPI](openapi/talkjs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/talkjs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/talkjs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TalkJS Messages API

Send, list, fetch, edit, and delete messages in a conversation, including UserMessage and SystemMessage types, replies via referencedMessageId, idempotency keys, and emoji reactions.

- **Human URL:** [https://talkjs.com/docs/Reference/REST_API/Messages/](https://talkjs.com/docs/Reference/REST_API/Messages/)
- **Base URL:** `https://api.talkjs.com/v1/{appId}`

#### Tags

- Messages
- Reactions
- Replies

#### Properties

- [Documentation](https://talkjs.com/docs/Reference/REST_API/Messages/)
- [API Reference](https://talkjs.com/docs/Reference/REST_API/Messages/)
- [OpenAPI](openapi/talkjs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/talkjs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/talkjs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TalkJS Import API

Import existing chat history with original timestamps via the special importing resource, used after upserting users and conversations to migrate from other chat providers into TalkJS.

- **Human URL:** [https://talkjs.com/docs/Reference/REST_API/Importing_Messages/](https://talkjs.com/docs/Reference/REST_API/Importing_Messages/)
- **Base URL:** `https://api.talkjs.com/v1/{appId}`

#### Tags

- Import
- Migration
- History

#### Properties

- [Documentation](https://talkjs.com/docs/Reference/REST_API/Importing_Messages/)
- [API Reference](https://talkjs.com/docs/Reference/REST_API/Importing_Messages/)
- [OpenAPI](openapi/talkjs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/talkjs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/talkjs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TalkJS Webhooks API

Server-to-server event delivery for message.sent, message.read, message.updated, message.deleted, user.created/updated, conversation.deleted, and notification lifecycle events, posted as JSON with an id/type/createdAt/data envelope to your configured endpoints.

- **Human URL:** [https://talkjs.com/docs/Reference/Webhooks/](https://talkjs.com/docs/Reference/Webhooks/)
- **Base URL:** `https://api.talkjs.com/v1/{appId}`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://talkjs.com/docs/Reference/Webhooks/)
- [API Reference](https://talkjs.com/docs/Reference/Webhooks/)
- [Review](review.yml)

## Common Properties

- [GitHub Organization](https://github.com/talkjs)
- [LinkedIn](https://www.linkedin.com/company/talkjs)
- [Website](https://talkjs.com)
- [Documentation](https://talkjs.com/docs/)
- [Plans](plans/talkjs-plans-pricing.yml)
- [Rate Limits](rate-limits/talkjs-rate-limits.yml)
- [Fin Ops](finops/talkjs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
