# TASKMODE NSIS Analyzer Build

Temporary **public build-only** repository for the TASK-103 NSIS analyzer evidence path.

## Scope

This repository is intentionally isolated from TASKMODE proprietary/runtime source and production infrastructure.

Allowed initial content:
- this purpose statement;
- an observation-only GitHub Actions workflow used to record hosted Windows runner/toolchain identity before any compilation.

Not allowed at this stage:
- TASKMODE proprietary/runtime source;
- credentials, secrets, VPS keys, privileged Supabase material;
- Gpg4win payloads;
- analyzer compilation/build;
- releases/packages/artifact publication;
- production or deployment actions.

The first Actions run is identity/provenance observation only. Any later analyzer build requires a separate reviewed authorization.
