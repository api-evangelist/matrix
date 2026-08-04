# Matrix (matrix)

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
