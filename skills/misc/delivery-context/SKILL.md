---
name: delivery-context
description: Prepare or resume a coding ticket with compact check results, evidence freshness and a bounded next action.
---

Use when a ticket starts, a check fails, or work resumes in a fresh session. Read the active ticket and its authorised command. Follow its selected source, test, accepted decision and handoff references. Load additional skills only if their trigger fits this job.

Use deterministic tools for search, compilation, lint and tests. Keep the full log locally. Return the outcome, exit status, named failure and assertion or diagnostic, omitted line count and log path. If a runner stops before a test reports an assertion, record the runner error. A passing command supplies evidence for its criterion only.

At a handoff record the attempted action, outcome, evidence location and the next concrete operation. Bind each observation to the source, test, configuration and result files on which it depends. On resume compare those inputs, reuse current observations and rerun only affected checks. A checkpoint cannot approve a decision, reopen the ticket or override its current stop.

For a repository with the Foundation delivery tools, use the project brief, compact gate result and checkpoint commands. Keep local commands and paths project-specific. For example, if a regression fixture changes after a failed test, refresh that result and retain an unrelated linter result whose inputs still match.
