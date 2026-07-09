# FH-RefToolkit

## Purpose and boundaries

Flathub reference toolkit with a Python package and standalone scripts.

This document is the internal governance and handoff entry point. Existing `README.md`, process documents, source, tests, and built artifacts remain project evidence and should be consulted for operational detail.

## Governance

- [Project manifest](FH-RefToolkit.manifest.toml)
- [Modification instructions](AGENTS.md)
- [CTS canonical standard](D:/.library/aptlantis_core/CTS/README.md)
- [Workspace Governance Standard](D:/.library/aptlantis_core/WGS/README.md)

## Current state

Governance metadata was reconciled on 2026-07-08: version `1.0.0`, lifecycle `paused`, stage `production`. Evidence reviewed: pyproject.toml, README.md, and FlathubRefs legacy manifest. The build, tests, shipping artifact, and release posture were not executed during this metadata pass, so this classification is not a release-readiness claim.

## Structure and relationships

This is registered as one independently governed project. `src` and `StandAloneScripts` are implementation surfaces, not separately governed child projects.

Legacy manifests, when listed in `FH-RefToolkit.manifest.toml`, are retained as migration evidence rather than parallel authority.

## Build and verification

Use pyproject.toml and README.md; verify packaged and standalone entry points separately.

Record verified commands, artifacts, versions, and current test results here as project-specific reconciliation proceeds.

## Known gaps and next review

- Confirm the project lifecycle and active-development state.
- Confirm build, run, test, packaging, and release commands from current source.
- Reconcile useful fields from legacy manifests without deleting historical evidence.
- Replace inferred descriptions with project-owner language where needed.
