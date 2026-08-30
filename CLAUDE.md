# God's Eye View - Claude Code Entry Point

God's Eye View is a unified visualization platform for understanding system architecture and dependencies.

## Quick Start

1. Read workspace documentation: `AGENTS.md`, `AI_WORKSPACE.md`, `PROJECT_CONTEXT.md`
2. Read project documentation: `PROJECT_CONTEXT.md`, `HANDOFF.md`, `TASKS.md`, `DECISIONS.md`, `TEST_PLAN.md`
3. Set up development environment following `TASKS.md`
4. Run tests and validation per `TEST_PLAN.md`

## Project Structure

```
gods-eye-view/
├── CLAUDE.md                 # This file - Claude Code entry point
├── PROJECT_CONTEXT.md        # Project overview and architecture
├── HANDOFF.md               # Current state and handoff info
├── TASKS.md                 # Current work items
├── DECISIONS.md             # Architectural decisions
├── TEST_PLAN.md             # Testing and validation strategy
├── src/                     # Source code
├── tests/                   # Test suite
├── docs/                    # Project documentation
└── .claude/                 # Claude Code configuration
    ├── settings.json
    └── skills/              # Project-specific skills
```

## Authority Documents

- `CLAUDE.md` - Claude Code entry point (this file)
- `PROJECT_CONTEXT.md` - Project goals, architecture, and constraints
- `HANDOFF.md` - Current state for continuation
- `TASKS.md` - Work tracking and current priorities
- `DECISIONS.md` - ADRs and architectural decisions
- `TEST_PLAN.md` - Testing strategy and validation gates
