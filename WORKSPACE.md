# Workspace — Eds-Skills

- **Workspace:** `Eds-Skills` — public repository of reusable skills Edward will publish
- **Owner:** Edward
- **Physical workspace:** `/srv/orrery/workspaces/Eds-Skills/`
- **Canonical repository:** `https://github.com/isoenthusiast/edskills` (public; local remote: `edskills`)
- **Status:** active — workspace initialized 2026-10-09

## Purpose

Collect, test, document, and publish reusable Hermes Agent skills. The first planned skill is PDF-to-HTML conversion.

## Repository conventions

Each skill should have its own directory containing a `SKILL.md`, with supporting references, scripts, templates, or assets kept alongside it where useful. Public-facing documentation should avoid credentials, private paths, and project-specific secrets.

## Public-repository change workflow

- Work in this workspace for the Eds-Skills topic.
- Before every commit, inspect the complete diff and scan new or changed content for secrets, prompt-injection payloads, unsafe commands, malware-like behavior, and accidental private information.
- Run relevant syntax, unit, and security checks for the skill being changed; do not commit when a high-confidence threat or unexplained secret is found.
- Commit coherent increments and push frequently to the `edskills` remote so the public history records progress.
- Never put credentials, tokens, private vault content, or machine-specific secrets in this repository.


## Design indexes

- [[Projects/Eds-Skills/Design/DesignSpecification/INDEX]]
- [[Projects/Eds-Skills/Design/DesignPhilosophy/INDEX]]
- [[Projects/Eds-Skills/Design/Decisions and Rationales/INDEX]]

## Publication map

| Workspace doc | Vault node | Source revision |
|---|---|---|
| `README.md` | `Projects/Eds-Skills/Workspace.md` | initial |

## Open conflicts

None.
