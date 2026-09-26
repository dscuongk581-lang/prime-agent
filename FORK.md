# Lean Runtime Fork

This fork is intentionally optimized for internal headless agent-runtime use.

## Keep

- RLM runtime and persistent Python kernel
- daemon/session lifecycle
- RPC/headless integration
- MCP integration
- skills and continual harness
- model providers
- core tests and runtime documentation

## Removed from the lean branch

- upstream community/maintainer GitHub automation
- upstream discussion and issue templates
- upstream benchmark/release workflows
- bundled example applications and extension demos
- local branding assets not required at runtime
- editor-specific upstream metadata

The goal is to keep runtime behavior intact while reducing maintenance surface and accidental CI cost.

Deeper removals such as TUI, provider families, or runtime features should happen only after the headless RPC integration is verified.
