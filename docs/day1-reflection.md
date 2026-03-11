# Day 1 – Engineering Reflection

## What Was Built

- Clean GitHub repository with SSH authentication
- Structured project folders (docs, labs, scripts)
- Homebrew environment with core CLI tooling
- Git identity configuration
- Terminal workflow baseline

## Problems Encountered

1. Nested repository created accidentally.
2. Folder naming inconsistency (case sensitivity).
3. Git identity not configured.
4. HTTPS authentication failed (password deprecated).
5. Shell entered broken quote state (`dquote>`).

## Root Causes

- Lack of attention to current working directory.
- Typos in CLI commands.
- Incomplete understanding of Git authentication methods.
- Improper quotation closure.

## Preventative Controls

- Always verify location with `pwd` before `git init`.
- Use `git remote -v` to validate remotes.
- Prefer SSH over HTTPS for GitHub.
- Recognize shell states before continuing execution.
- Read error messages fully before retrying commands.

## Technical Concepts Reinforced

- SSH key generation and agent usage.
- Git global configuration.
- Repo initialization and remote linking.
- Directory management and CLI discipline.

## Meta Skill Developed

- Error recovery without panic.
- Iterative debugging.
- Controlled execution under instruction.

## Time Spent

Approx: 90_ minutes
