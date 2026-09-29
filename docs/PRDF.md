# PRDF (production-readiness audit)
Inspected: 2026-09-28. Method: provenance + code-truth inspection - README ignored per owner order.

## VERDICT: FORK - payloadcms/payload (full Payload CMS monorepo, 168MB)
Stale since Dec 2025.
## FINDINGS
1. HIGH - 168MB upstream CMS framework clone; rancho-santiago intent unclear (a client project started from the framework repo instead of a scaffold?). 2. If a rancho-santiago site exists, it should live in its own repo with Payload as a dependency, not a fork.
## PORTFOLIO ROLE
Exclude. Recommend ARCHIVE after owner confirms no local-only work inside (deletion law: manifest first).