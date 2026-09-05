# BookNote-Offline

Firefox extension source project reconstructed from the v7.10.38 XPI release artifact.

## Source of truth
- Development branch: `refactor/source-engineering`
- Release baseline: `BookNote-Offline-v7.10.38-Supertonic-ZH-Quality-Stability-no-supertonic.xpi`

## Scope
This source snapshot intentionally excludes the removed local Supertonic 3 and Supertonic-ZH ONNX engines. The release artifact remains in the repository root for traceability.

## Layout
- `src/extension/` — unpacked extension source
- `docs/` — development notes and audits
- `dist/` — generated XPI releases
- `tests/` — validation scripts and regression tests

The initial source import is based on the unpacked XPI; subsequent changes should be made in source and rebuilt into `dist/` rather than editing the XPI directly.
