# Hermes Agent Handoff

This repo stores operational handoff notes for Naelvi's separated Hermes coding
agent setup.

Current focus:

- Keep the existing RP Hermes instance untouched.
- Run a separate Telegram coding agent as `hermes-code`.
- Route casual Indonesian coding requests into a small multi-agent workflow.
- Use 9Router locally on the VPS for model routing and usage tracing.

Start here:

- [docs/HANDOFF_2026-07-01.md](docs/HANDOFF_2026-07-01.md)

No secrets are stored in this repo. API keys, Telegram tokens, and private SSH
keys stay on the VPS or the operator machine.
