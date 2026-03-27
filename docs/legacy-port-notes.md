# Legacy Port Notes

Last updated: 2026-03-27

## Purpose

Capture behavior contracts from the external legacy game repo in a portable way that can live inside this repository.

Rule:
- The external repo is reference material only.
- Once a subsystem has local tests in this repo, those tests become the normative source of truth.

For each subsystem record:
- Input and output shapes
- Deterministic seed expectations
- Important invariants and failure cases
- Renamed 2044 terminology
- Any intentional deviations from legacy behavior

## Port Workflow

1. Inspect the legacy subsystem in the external repo.
2. Summarize behavior here in plain language.
3. Add deterministic tests under `shared/game/__tests__`.
4. Port the implementation into `shared/game`.
5. Note any deviations before merging.

## Subsystems

### RNG

Status:
- Not yet ported.

Contract notes:
- TBD

### World Generation

Status:
- Not yet ported.

Contract notes:
- TBD

### World Validation

Status:
- Not yet ported.

Contract notes:
- TBD

### Objective State

Status:
- Not yet ported.

Contract notes:
- TBD

### Combat Initiative And Round Advancement

Status:
- Not yet ported.

Contract notes:
- TBD
