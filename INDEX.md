# zssh Repository Index

This file is the canonical navigation entry point for the repository.

## Governing documents

Upload the supplied documents to these exact paths:

1. `docs/INVARIANTS.md`
2. `docs/ANTI-INVARIANTS.md`
3. `docs/SACRIFICES.md`
4. `docs/SCOPE.md`
5. `docs/ARCHITECTURE.md`
6. `docs/VARIANTS.md`
7. `docs/SECURITY.md`
8. `docs/DECISIONS.md`
9. `docs/BUILD.md`
10. `docs/CERTIFICATION.md`

## Research and provenance

- `SSH-RESEARCH-AND-ARCHITECTURE.md`
- `CHANGES-FROM-ORIGINAL.md`
- `SOURCES.md`
- `SHA256SUMS.txt`
- `AGENTS.md`

## Repository areas

- `docs/` — governing architecture and product law
- `src/` — implementation source
- `tests/` — automated tests and certification harnesses
- `scripts/` — deterministic development and release commands
- `evidence/` — generated test and certification evidence
- `assets/` — pinned asset manifests and non-source inputs
- `packaging/` — installation, service, and release packaging

## Document precedence

Until the project document is revised, the intended precedence is the numbered governing-document order above. Research and provenance files explain the decisions but do not override governing documents.

## Current status

The repository structure is initialized. Governing documents are intentionally not preloaded so project naming and the project document can be updated before the first architecture commit.
