---
name: github-issues
description: Create, label, or triage a GitHub issue for this repository. Defines title prefixes, label baseline, and lifecycle labels.
---

# GitHub Issues

- Start from the matching template in `.github/ISSUE_TEMPLATE/`. The template's fields define the body.
- Start the title with a type prefix: `[BUG]: ...`, `[FEATURE]: ...`, `[DOCS]: ...`, `[TESTING]: ...`, `[CHORE]: ...`. Epics use `[EPIC][SCOPE]: ...`.
- Label baseline: one primary type label (`bug`, `enhancement`, `documentation`, `testing`, `chore`) plus `triage` on new issues. Add 1-3 optional scope labels (`security`, `performance`, `ui`, `api`, `python`, `devops`, `a2a`, `mcp-protocol`). Epics add `epic`.
- Lifecycle labels: `awaiting-user` when blocked on reporter feedback, `blocked` for dependency blockers, `planned` when accepted but deferred, `fixed` only after the resolving change merges.
- Bodies and comments follow *Agent Prose* in `AGENTS.md`. Before you post, rewrite them with the `asd-ste100` skill in STE-flavored mode. For public tone, see the `pr-review` skill, section *Tone*.
