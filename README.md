# Matrix (matrix)

Matrix is an open standard and decentralized protocol for real-time communication, providing federated messaging, voice, video, and IoT signalling across independently operated homeservers. The Matrix specification defines several REST APIs (Client-Server, Server-Server, Application Service, Identity Service, and Push Gateway) that interoperate across the federation. Authentication is typically performed via Bearer access tokens, with newer flows using OAuth 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/matrix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/matrix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Messaging
- Decentralized
- Federated
- Open Standard
- Real-Time Communication
- VoIP

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Matrix Client-Server API

REST API used by Matrix clients to communicate with a homeserver, covering login, room creation and management, message sending, sync, device management, end-to-end encryption, and push notifications. Authentication uses Bearer access tokens issued by the homeserver, with OAuth 2.0 supported in newer versions.

- **Human URL:** [https://spec.matrix.org/latest/client-server-api/](https://spec.matrix.org/latest/client-server-api/)
- **Base URL:** `https://matrix.org/_matrix/client`

#### Tags

- Client-Server
- Messaging
- Rooms
- Sync
- Encryption

#### Properties

- [Documentation](https://spec.matrix.org/latest/client-server-api/)
- [Open A P I  Source](https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server)
- [Postman Collection](collections/matrix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matrix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Matrix Server-Server (Federation) API

Federation API that lets Matrix homeservers exchange events, presence, and key information with one another over signed JSON requests.

- **Human URL:** [https://spec.matrix.org/latest/server-server-api/](https://spec.matrix.org/latest/server-server-api/)
- **Base URL:** `https://matrix.org/_matrix/federation`

#### Tags

- Federation
- Server-Server
- Decentralized

#### Properties

- [Documentation](https://spec.matrix.org/latest/server-server-api/)
- [Open A P I  Source](https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server)
- [Postman Collection](collections/matrix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matrix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Matrix Application Service API

API used by application services (bridges, bots) to integrate with a homeserver, claim namespaces, and exchange events.

- **Human URL:** [https://spec.matrix.org/latest/application-service-api/](https://spec.matrix.org/latest/application-service-api/)
- **Base URL:** `https://matrix.org/_matrix/app`

#### Tags

- Bridges
- Bots
- Integrations

#### Properties

- [Documentation](https://spec.matrix.org/latest/application-service-api/)
- [Open A P I  Source](https://github.com/matrix-org/matrix-spec/tree/main/data/api/application-service)
- [Postman Collection](collections/matrix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matrix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Matrix Identity Service API

API for looking up Matrix user IDs from third-party identifiers such as email addresses and phone numbers via federated identity servers.

- **Human URL:** [https://spec.matrix.org/latest/identity-service-api/](https://spec.matrix.org/latest/identity-service-api/)
- **Base URL:** `https://matrix.org/_matrix/identity`

#### Tags

- Identity
- Lookup
- 3PID

#### Properties

- [Documentation](https://spec.matrix.org/latest/identity-service-api/)
- [Open A P I  Source](https://github.com/matrix-org/matrix-spec/tree/main/data/api/identity)
- [Postman Collection](collections/matrix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matrix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Matrix Push Gateway API

Push Gateway API homeservers use to deliver notifications to mobile push services on behalf of Matrix clients.

- **Human URL:** [https://spec.matrix.org/latest/push-gateway-api/](https://spec.matrix.org/latest/push-gateway-api/)
- **Base URL:** `https://matrix.org/_matrix/push`

#### Tags

- Push Notifications
- Mobile

#### Properties

- [Documentation](https://spec.matrix.org/latest/push-gateway-api/)
- [Open A P I  Source](https://github.com/matrix-org/matrix-spec/tree/main/data/api/push-gateway)
- [Postman Collection](collections/matrix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matrix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/matrix-org)
- [Website](https://matrix.org)
- [Documentation](https://spec.matrix.org/latest/)
- [Specification  Repository](https://github.com/matrix-org/matrix-spec)
- [GitHub Organization](https://github.com/matrix-org)
- [Sign Up](https://matrix.org/try-matrix/)
- [Support](https://matrix.org/support/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
