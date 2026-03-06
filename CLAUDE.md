# CLAUDE.md

This file provides guidance for AI assistants (e.g. Claude Code) working in this repository.

## Repository Overview

**hello-world** is a minimal starter repository created by [@Andreocardoso](https://github.com/Andreocardoso). As of March 2026, it contains only a `README.md` and has no application code, build system, tests, or dependencies.

## Current State

| Item | Status |
|---|---|
| Language / framework | Not yet defined |
| Package manager | Not yet defined |
| Test suite | None |
| CI/CD | None |
| Linter / formatter | None |

## Repository Structure

```
hello-world/
└── README.md   # Project title and placeholder description
```

## Development Workflow

Because the project has no established tooling, the workflow below describes sensible defaults to adopt when code is first added.

### Branching

- Default branch: `master`
- Feature branches: `<username>/<short-description>` or `claude/<short-description>-<session-id>`
- Never push directly to `master`; open a pull request instead

### Commits

- Write short, imperative commit messages (e.g. `Add README badges`, `Fix typo in docs`)
- Keep commits focused on a single concern

### Adding Code

When the first language/framework is chosen, update this file with:
1. The language and version requirement
2. How to install dependencies
3. How to run the project locally
4. How to run tests
5. Any linting or formatting commands

## Conventions for AI Assistants

- **Read before editing.** Always read a file before modifying it.
- **Minimal changes.** Only change what is necessary for the task at hand.
- **No speculative files.** Do not create files that are not required by the current task.
- **No extra dependencies.** Do not add packages or libraries unless explicitly requested.
- **Update this file** whenever significant tooling, structure, or workflow changes are made to the project.
