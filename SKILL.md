---
name: codex-usage
description: Check Codex CLI usage quickly and concisely via the local codex-usage tool. Use when the user asks about Codex usage, spend, limits, or current billing/consumption status.
---

# Codex Usage

Run the local CLI and return the plain output.

## Command

```bash
codex-usage --plain
```

## Notes

- Use `exec` for the command.
- Return concise results directly.
- If the command fails, show stderr and suggest the next corrective step.
