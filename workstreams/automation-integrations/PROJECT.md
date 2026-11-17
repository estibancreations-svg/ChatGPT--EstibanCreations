# EC Systems — Automation, Integrations & Quality Gates

**Status:** Proposed separate ChatGPT conversation, not created by tool.  
**Updated:** 2026-11-17 (America/Chicago)

## Mission
Integrate EC StoryWorks with existing VisionWeaver and THELMA controls, GitHub, Vercel, Supabase, Runway and approved YouTube/commerce APIs without duplicating owner systems.

## Constraints
- Verify canonical VisionWeaver, THELMA and orchestration repositories before code changes.
- Preserve owner/admin authority, least privilege, zero-trust boundaries, one-way reports, cost caps and documented approvals.
- Never place secrets or proprietary contracts in public GitHub.
- Use deployment Quality Gates: tests, permissions/security, integration tests, manual QA and final Administrator sign-off.
- Runway primary; 7Art integration requires documented integration method and commercial terms.
- Integrations must not make paid API calls, sign agreements, publish or message third parties without authorization.

## Working steps
Repository audit → data contracts → authorization design → staging adapters → QA → deployment evidence → pilot → production rollout.
