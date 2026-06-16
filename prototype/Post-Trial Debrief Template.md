# Post-Trial Debrief Template: Agent Loop Runbook Library

Use this immediately after a real long-running agent loop trial. It is a fillable debrief for turning the runbook output and evidence into precise README/prototype/skill patches. It is template-ready; it is not evidence that a trial has happened.

## Trial reference

- Trial date:
- Operator:
- Loop type tested:
- Target repo/system:
- Related packet: [[First Real Trial Packet]]
- Related decision card: [[Promotion Decision Card]]
- Prototype used: [[agent-loop-runbook-builder.html]]

## Evidence attached

| Evidence item | Link/path | What it proves | Any redaction needed? |
| --- | --- | --- | --- |
| Generated loop runbook markdown |  |  |  |
| Agent command/log transcript |  |  |  |
| Polling/checkpoint notes |  |  |  |
| Stop/escalation decision evidence |  |  |  |
| Outcome artifact or issue/PR link |  |  |  |

## What changed after real use?

### Keep
- 

### Patch before reuse
- 

### Remove or de-scope
- 

### New risk found
- 

## Claim-to-evidence check

| Existing claim | Evidence status | Patch needed before saying it publicly? |
| --- | --- | --- |
| The runbook format improves long-running loop reliability | unknown / supported / contradicted |  |
| Stop criteria and polling cadence were clear enough for operation | unknown / supported / contradicted |  |
| The pattern is reusable beyond one task class | unknown / supported / contradicted |  |

## Patch queue

- [ ] Update package README with only evidence-backed wording.
- [ ] Update prototype README with real usage notes or known blockers.
- [ ] Patch `agent-loop-runbook-builder.html` if the trial exposed missing fields or unsafe defaults.
- [ ] Patch the skill draft only after evidence supports a repeatable procedure.
- [ ] Update [[../Improvement-Loops/Agent Loop Runbook Library Loop]] with the completed outcome.

## Debrief decision

Choose one after completing the evidence table and Promotion Decision Card:

- [ ] Promote wording for broader reuse.
- [ ] Keep pilot-only and schedule another trial.
- [ ] Iterate prototype before reuse.
- [ ] Retire or merge into another artifact.

## Notes

-
