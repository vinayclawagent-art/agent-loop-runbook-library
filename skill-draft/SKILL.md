---
name: agent-loop-runbooks
description: "Reusable workflow draft derived from Cursor Loops as Operational Agent Runbooks"
version: 0.1.0
author: Hermes Agent
---

# agent-loop-runbooks

## Trigger
Use when a coding-agent task needs the workflow described by [[Cursor Loops as Operational Agent Runbooks]].

## Procedure
1. Write the user-visible goal and expected artifact.
2. Split the run into bounded steps with explicit context, commands, evidence, and stop conditions.
3. Run the smallest safe trial first; do not claim validation until real evidence is attached.
4. Return a decision: promote, pilot-only, iterate, or hold.

## Pitfalls
- Do not delegate vague tasks without success metrics.
- Do not let long-running loops mutate production or secrets without a stop rule.
- Keep evidence and command output attached to the final handoff.

## Source
- X note: [[Cursor Loops as Operational Agent Runbooks]]
- Package: [[Agent Loop Runbook Library]]
