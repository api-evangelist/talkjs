# TalkJS (talkjs)

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
