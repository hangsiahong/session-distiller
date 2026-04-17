# Session Distiller 🧬

A skill to solve "Context Bloat" and "Subagent Fog". It distills long conversations into high-density, token-efficient checkpoints.

## Installation

```bash
# Clone into your skills directory
gh repo clone hangsiahong/session-distiller
```

## Quick Start

1. **Ask for a distillation**: "Distill our session for a subagent that will fix the CSS."
2. **Copy the output**.
3. **Spawn a subagent**: Use the distilled output as the prompt for `spawn_agent`.

## Why use this?

Standard AI history is full of tool outputs, mistakes, and repetitive thoughts. **Session Distiller** filters the noise so your subagents (and you) can focus on the signal.

## Features

- **Subagent Handoff**: Tailored context for workers.
- **Session Restart**: Save state to a memory and resume later.
- **Token Optimization**: Fits complex state into <500 tokens.

Built by [hangsiahong](https://github.com/hangsiahong).
