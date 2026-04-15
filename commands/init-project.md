---
description: Initialize project
allowed-tools:
  - Bash(*)
  - Read
  - Edit
  - TodoWrite
---

# Init Project

1. If inside a git repo with uncommitted changes — ask user whether to commit first, continue without commit, or stop.
2. Verify `.claude/skills/project-knowledge/` exists. Create it if not.
3. Security check: look for sensitive files (`.env*`, `*.key`, `*.pem`, `credentials.json`, `secrets/`) not covered by `.gitignore`. If found — add to `.gitignore` before proceeding.

Show user:
- Next step: run `project-planning` skill to fill project documentation
