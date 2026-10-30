# Matrix

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

Matrix is an open standard and decentralized protocol for real-time communication, providing federated messaging, voice, video, and IoT signalling across independently operated homeservers. The Matrix specification defines several REST APIs (Client-Server, Server-Server, Application Service, Identity Service, and Push Gateway) that interoperate across the federation. Authentication is typically performed via Bearer access tokens, with newer flows using OAuth 2.0.

**Areas:** Messaging · Decentralized · Federated · Open Standard · Real-Time Communication · VoIP · Matrix

## Matrix on APIs.io

Everything profiled for Matrix is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/matrix/](https://apis.io/providers/matrix/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [Matrix Client-Server API](https://apis.io/apis/matrix/client-server-api/) — REST API used by Matrix clients to communicate with a homeserver, covering login, room creation and management, message sending, sync, device management,…
- [Matrix Server-Server (Federation) API](https://apis.io/apis/matrix/server-server-api/) — Federation API that lets Matrix homeservers exchange events, presence, and key information with one another over signed JSON requests.
- [Matrix Application Service API](https://apis.io/apis/matrix/application-service-api/) — API used by application services (bridges, bots) to integrate with a homeserver, claim namespaces, and exchange events.
- [Matrix Identity Service API](https://apis.io/apis/matrix/identity-service-api/) — API for looking up Matrix user IDs from third-party identifiers such as email addresses and phone numbers via federated identity servers.
- [Matrix Push Gateway API](https://apis.io/apis/matrix/push-gateway-api/) — Push Gateway API homeservers use to deliver notifications to mobile push services on behalf of Matrix clients.
- [Matrix Account API](https://apis.io/apis/matrix/matrix-account-api/) — The Account API from Matrix — 1 operation(s) for account.
- [Matrix Capabilities API](https://apis.io/apis/matrix/matrix-capabilities-api/) — The Capabilities API from Matrix — 1 operation(s) for capabilities.
- [Matrix CreateRoom API](https://apis.io/apis/matrix/matrix-createroom-api/) — The CreateRoom API from Matrix — 1 operation(s) for createroom.
- [Matrix Devices API](https://apis.io/apis/matrix/matrix-devices-api/) — The Devices API from Matrix — 1 operation(s) for devices.
- [Matrix Directory API](https://apis.io/apis/matrix/matrix-directory-api/) — The Directory API from Matrix — 1 operation(s) for directory.
- [Matrix Join API](https://apis.io/apis/matrix/matrix-join-api/) — The Join API from Matrix — 1 operation(s) for join.
- [Matrix Keys API](https://apis.io/apis/matrix/matrix-keys-api/) — The Keys API from Matrix — 1 operation(s) for keys.
- [Matrix Login API](https://apis.io/apis/matrix/matrix-login-api/) — The Login API from Matrix — 1 operation(s) for login.
- [Matrix Logout API](https://apis.io/apis/matrix/matrix-logout-api/) — The Logout API from Matrix — 1 operation(s) for logout.
- [Matrix Profile API](https://apis.io/apis/matrix/matrix-profile-api/) — The Profile API from Matrix — 2 operation(s) for profile.
- [Matrix PublicRooms API](https://apis.io/apis/matrix/matrix-publicrooms-api/) — The PublicRooms API from Matrix — 1 operation(s) for publicrooms.
- [Matrix Refresh API](https://apis.io/apis/matrix/matrix-refresh-api/) — The Refresh API from Matrix — 1 operation(s) for refresh.
- [Matrix Register API](https://apis.io/apis/matrix/matrix-register-api/) — The Register API from Matrix — 1 operation(s) for register.
- [Matrix Rooms API](https://apis.io/apis/matrix/matrix-rooms-api/) — The Rooms API from Matrix — 4 operation(s) for rooms.
- [Matrix Sync API](https://apis.io/apis/matrix/matrix-sync-api/) — The Sync API from Matrix — 1 operation(s) for sync.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Matrix Client-Server Sync API](https://apis.io/asyncapis/matrix/matrix-sync-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/v3/sync](https://apis.io/channels/matrix/v3-sync/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Matrix Agentic Access](https://apis.io/agentic-access/matrix/matrix-agentic-access/)

#### Collections (16)

Postman and Open Collection request collections.

- [Matrix Client-Server API](https://apis.io/collections/matrix/open-matrix/)
- [Matrix Client-Server Account API](https://apis.io/collections/matrix/open-matrix-account-api/)
- [Matrix Client-Server Account Capabilities API](https://apis.io/collections/matrix/open-matrix-capabilities-api/)
- [Matrix Client-Server Account CreateRoom API](https://apis.io/collections/matrix/open-matrix-createroom-api/)
- [Matrix Client-Server Account Devices API](https://apis.io/collections/matrix/open-matrix-devices-api/)
- [Matrix Client-Server Account Directory API](https://apis.io/collections/matrix/open-matrix-directory-api/)
- [Matrix Client-Server Account Join API](https://apis.io/collections/matrix/open-matrix-join-api/)
- [Matrix Client-Server Account Keys API](https://apis.io/collections/matrix/open-matrix-keys-api/)
- [Matrix Client-Server Account Login API](https://apis.io/collections/matrix/open-matrix-login-api/)
- [Matrix Client-Server Account Logout API](https://apis.io/collections/matrix/open-matrix-logout-api/)
- [Matrix Client-Server Account Profile API](https://apis.io/collections/matrix/open-matrix-profile-api/)
- [Matrix Client-Server Account PublicRooms API](https://apis.io/collections/matrix/open-matrix-publicrooms-api/)
- [Matrix Client-Server Account Refresh API](https://apis.io/collections/matrix/open-matrix-refresh-api/)
- [Matrix Client-Server Account Register API](https://apis.io/collections/matrix/open-matrix-register-api/)
- [Matrix Client-Server Account Rooms API](https://apis.io/collections/matrix/open-matrix-rooms-api/)
- [Matrix Client-Server Account Sync API](https://apis.io/collections/matrix/open-matrix-sync-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Matrix — asyncapi rules](https://apis.io/rules/matrix/matrix-asyncapi-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Matrix Authentication](https://apis.io/security/matrix/matrix-authentication/)
- [Matrix Domain Security](https://apis.io/security/matrix/matrix-domain-security/)
- [Matrix Vulnerability Disclosure](https://apis.io/security/matrix/matrix-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://matrix.org)
- [Documentation](https://spec.matrix.org/latest/)
- [Support](https://matrix.org/support/)
- [Blog](https://matrix.org/blog/feed/)
- [GitHub](https://github.com/matrix-org)

## API Evangelist rating

**Kin Score 28.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 49.7 |
| Contract governance | 11.4 |
| Operational transparency | 2.6 |
| Developer ergonomics | 28.6 |
| Access clarity | 13.2 |

**Agent readiness 18.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 17.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/matrix/](https://apis.io/providers/matrix/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Matrix: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/matrix/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
