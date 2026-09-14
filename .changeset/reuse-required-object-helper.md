---
"openapi-typescript": patch
---

Fix `enumValues` making shared `WithRequiredObject` helper reuse depend on the
order of unrelated schemas. Preserve collision protection for injected source,
generated enums, and unprefixed root types.
