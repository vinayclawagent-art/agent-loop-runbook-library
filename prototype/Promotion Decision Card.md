# Promotion Decision Card: Agent Loop Runbook Library

Status: template-ready; no validation proof recorded yet.

Use this card after the [[First Real Trial Packet]] is filled from a real runbook trial. Do not choose a promotion outcome from memory, vibes, or the source X post alone.

## 1. Trial identity

- Decision date:
- Operator:
- Real task / repo / system:
- Trial packet: [[First Real Trial Packet]]
- Builder output / handoff link:
- Evidence folder / issue / PR:
- Reviewer:

## 2. Evidence completeness gate

| Required evidence | Link / path | Present? | Notes |
| --- | --- | --- | --- |
| Generated runbook markdown |  |  |  |
| Agent transcript / logs |  |  |  |
| Output diff / artifact / decision |  |  |  |
| Metric before/after or operator judgment |  |  |  |
| Stop/escalation event or explicit "none occurred" note |  |  |  |

If any required row is missing, choose **iterate** or **hold**; do not promote.

## 3. Promotion criteria

Score each criterion 1-5 using evidence from the packet.

| Criterion | Score | Evidence link / note | Threshold |
| --- | ---: | --- | --- |
| Target metric was concrete and measurable |  |  | 4+ |
| Polling cadence avoided spam and stale waiting |  |  | 4+ |
| Stop criteria prevented unsafe or endless looping |  |  | 4+ |
| Escalation path captured ambiguity early |  |  | 4+ |
| Output is reusable for a future loop |  |  | 4+ |
| Operator overhead stayed lower than ad hoc prompting |  |  | 4+ |

## 4. Decision

Choose exactly one after evidence is attached:

- [ ] **Promote** — add to a reusable runbook/skill path.
- [ ] **Pilot-only** — use on one more live task before promotion.
- [ ] **Iterate** — patch builder fields or README before another trial.
- [ ] **Hold / retire** — loop added risk, confusion, or too much overhead.

Decision rationale:

## 5. Patch queue

Only patch public/package claims after the decision above is evidence-backed.

- README change:
- Prototype builder field/copy change:
- Skill draft change:
- Infographic/explanation change:
- Filled example to add:
- Loop next_focus update:

## Guardrail

Every positive claim needs a link to the trial packet, logs, issue/PR, screenshot, or evaluator note. If the proof is not attached, leave the claim as "template-ready" rather than "validated".
