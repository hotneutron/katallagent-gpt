Working rules. Keep them terse.

## Authority

- Local behavior: this file.
- Bundle mechanics: `cross-team/AGENTS.md`.
- Shared product framing: `katallagent/README.md`; ratified decisions:
  `katallagent/.plan/DECISIONS.md`.
- Dirty working trees are evidence of local state, not committed truth.
- Specificity is not authority; verify speculative claims before building on
  them.

## Work Rules

Before proposing: name the source artifact and its authority.

Before implementing a novel mechanism, protocol, market-design surface, or
credit-assignment rule: cite or produce an existing-art study, or explicitly
mark the study-gate warning.

After adding an instrument, axis, report, check, or simulator surface, exercise
the new observability before moving on, or explicitly record why it is
deferred.

## Repo Style

- Keep root docs focused on this lane.
- `katallagent/` is a symlink to the shared implementation repo
  `../katallagent`; both lanes read and modify it directly. Parallax rules do
  not apply there. Studies live under `katallagent/lab/`; implementation lands
  outside `lab/`.
- Design and debate stay in this lane's `.plan/`; ratified decisions go in
  `katallagent/.plan/DECISIONS.md`.
- Name docs `{YYMMDD}-{HHMM}-{type}-{topics}.md`; get timestamps from `date`.
- Doc types and authority mappings are defined by `cross-team.json`.
- Any amendment to an existing artifact must add or update a timestamped
  `## Revision History`.
- Prefer local adoption notes over copied partner history.
- No `Co-Authored-By` trailer.
- Do not push unless the user explicitly asks.
