# Localization Studio

Translation, i18n and regional content

Translate and manage i18n strings, glossaries, and translation memory. Package language bundles, adapt RTL layouts and regional content, localize subtitles and voiceovers, review machine translations, and run linguistic QA before launch.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (7):**

| Service | Status |
|---|---|
| `localization-service` | Suggested — not yet built |
| `knowledge-service` | Core |
| `document-service` | Core |
| `media-service` | New (Tier-1) |
| `publishing-service` | Core |
| `workflow-service` | Core |
| `model-service` | Core |
