# ChatGPT--EstibanCreations

Central organization hub for Estiban Creations conversation-derived project plans, working specifications, change histories and links to verified implementations.

> **Repository visibility: PUBLIC.** Do not commit private conversation transcripts, keys, tokens, financial records, customer contact details, unpublished contractual terms, or protected media assets. Store sensitive material in authorized private systems and refer to redacted identifiers here.

## Project index

| Area | Source of truth | Purpose |
|---|---|---|
| EC StoryWorks | [Operating Blueprint](storyworks/README.md) | Autonomous novella production and revenue business module |
| EC StoryWorks | [Updates & Decisions](storyworks/UPDATES.md) | Dated intake, approval decisions, implementation evidence and next actions |
| EC Punch Lab | [Testing Framework](punch-lab/README.md) | Controlled Runway/7Art/tool comparison and QC |
 
## Organization standard

Each project should maintain a README with scope, authority, dependencies, actual status and links to related systems, plus dated update entries and evidence where available. Discussions are **source material**, not proof of a deployed integration. Link to specific issues, commits, pull requests, deployments and test runs when verifying completion.

**Governance:** Estiban Creations is the final approving authority for production spending, publication, brand commitments, contracts and external account changes. THELMA automation operates only within explicitly granted and auditable limits.

**Current baseline date:** 2026-11-17.

## Hosting decision and deployment mapping

Estiban Creations selected **Render** for application hosting. Existing Supabase projects continue to provide PostgreSQL, authentication and storage where applicable. This repository's placement is **Reference archive · no service**. Preserve the index of conversations and evidence. Link deployment decisions and changes from the owning runtime repository.

The GrantOS review verified 27 failed Vercel preview checks across nine commit SHAs, a temporary successful preview checkpoint and a separate production availability block. See the [repository mapping and evidence](docs/RENDER-MIGRATION-MAP.md) for context and release requirements.
