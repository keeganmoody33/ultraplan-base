# CLAUDE.md

## Project intent
This repository is a reusable starter for Claude Code on the web and local Claude workflows.
Optimize for clear plans, safe edits, small diffs, and reusable project structure.

## Core workflow
- Start by understanding the repo and restating the goal briefly.
- For non-trivial work, create a short plan before editing.
- Prefer small, reversible changes over sweeping rewrites.
- Preserve existing patterns unless there is a strong reason to change them.
- When introducing a new pattern, explain why.
- After edits, run the most relevant validation available.

## Editing rules
- Do not rename files or move directories unless necessary.
- Do not add dependencies unless required.
- Do not invent requirements; call out assumptions clearly.
- Keep comments sparse and useful.
- Prefer readable code over clever code.
- Keep functions focused and names explicit.

## Git and change hygiene
- Keep diffs tight and task-scoped.
- Avoid touching unrelated files.
- Summarize what changed, why, and any follow-up work.
- If validation cannot be run, say exactly why.

## Planning behavior
- Use ultraplan / planning mode for architecture, migrations, refactors, and multi-file work.
- Break large tasks into ordered steps.
- Surface risks, blockers, and assumptions early.
- Prefer execution only after the plan is coherent.

## Repo conventions
- Shared project guidance lives here.
- More specific rules live in `.claude/rules/`.
- Personal-only preferences belong in `CLAUDE.local.md`, not here.
- If `AGENTS.md` exists, import it here instead of duplicating guidance.

## Definition of done
- The requested task is completed.
- Relevant checks were run, or blockers were explained.
- The final output is concise and directly useful.
