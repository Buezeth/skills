# Agent Conventions

This file defines guidelines and behavioral conventions for AI agents operating in this repository.

## Philosophy

- **The engineer decides; the AI recommends.** Any AI-initiated verification, critique, or exploration is offered and surfaced, never unilaterally enforced or auto-applied without approval.
- **Suggestions, never gates.** Workflow stages are recommendations. The user retains autonomy over execution order and completion declarations.
- **Clear recommendations.** Always present exactly one recommended option with a single-line explanation for decision prompts.
- **Lean skills.** Skills in `skills/` load on-demand into context; minimize non-operational commentary and preserve low token overhead.
