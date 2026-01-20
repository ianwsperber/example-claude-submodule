---
description: Example repo-specific command that greets the user
---

# Hello Command

This is an example repo-specific command. It demonstrates how individual repositories within the monorepo can define their own Claude commands.

When invoked, greet the user and tell them:
1. They are working in the `example-claude-submodule` repository
2. Their favorite color is indigo (from the repo's AGENTS.md)
3. The parent monorepo's favorite color is chartreuse (inherited context)

This demonstrates how CLAUDE.md context is inherited from parent directories in a monorepo structure.
