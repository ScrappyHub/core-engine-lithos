# LITHOS REQUIRED ARTIFACTS (Canonical V1)

Engine Key: **LITHOS**  
Semantics: **RAW_TRUTH**  
Authority: Engine Repo (Binding addendum; enforced by CORE Runtime)

This document is an addendum to:
`ScrappyHub/Core-platform/GOVERNANCE/RUN_BUNDLE_SPEC.md`

LITHOS is a TRUTH_ENGINE. It emits geology/materials domain truth only.

---

## Required (in addition to standard RUN_BUNDLE spec)

No additional artifacts are required beyond the standard CORE run bundle.

---

## Required Output Fields (RUN_OUTPUT.json)

RUN_OUTPUT.json MUST satisfy the engine OUTPUT_SCHEMA and MUST include:
- `semantics = RAW_TRUTH`
- `inputs_hash`
- `outputs_hash`

---

## Prohibitions

LITHOS output MUST NOT include:
- ownership/extraction/economic recommendations (vertical lens only)
- causal/attribution/intent claims
- identity/governance/billing fields
- peer delivery indicators (inputs are delivered by CORE only)
