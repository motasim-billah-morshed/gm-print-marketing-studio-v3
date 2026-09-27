# GM Print v3 development scope

- Owner instruction (2026-09-27): v3 is a separate copy of the accepted v2 Delivery 2 baseline, commit f6a8608ee0451043020f48602ce383a0a2375307. Work only in gm-print-marketing-studio-v3 for the next delivery. Do not modify v1 or v2 repositories, branches, tags, data or live sites.
- This preparation authorizes copying and version documentation only. Await the owner's v3 delivery instructions before feature development. Rejected D3 foundation code, UI, credentials and database are not part of this baseline; do not reintroduce them without explicit authorization.
- Preserve the accepted visual theme, navigation and workflows. Do not replace them with a separate interface. Every future delivery must begin in a new version copy as requested by the owner; preserve the previous version for comparison.
- V3-SOURCE.md defines the exact baseline. Earlier v2 scope statements in inherited architecture/versioning documents are historical; this instruction controls the active development destination.
- Never move/delete the v1 tag or force-push the baseline history.
- Preserve M01–M16 and the existing 64 submodule / 192 workflow IDs.
- Read ARCHITECTURE-REVIEW.md before implementing. It is a proposed review, not approved architecture. Resolve critical decisions with the owner before dependent implementation.
- Preserve the ERP boundary: no salesperson assignment, quotation, order, payment or sales KPI implementation here.
- No real personal data, credentials or production connection secrets in the public demo/repository.
- Each development unit needs requirement, design, implementation, automated/integration/acceptance evidence and documentation. Demo checks do not prove production acceptance.
- Update CHANGELOG.md and build bundle.js after source edits. Run node qc.mjs for prototype regressions.
- Use codex/ branches for feature development; keep main reviewable and compare with v1.
