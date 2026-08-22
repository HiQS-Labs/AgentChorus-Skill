# Agent2Agent

Agent2Agent is a lightweight, skill-first way for two or more supported coding-agent sessions to
exchange useful context through a serialized local discussion. It works across supported terminals,
harnesses, models, and interfaces without requiring a hosted service or database.

## Quick start

```bash
bash skills/agent2agent/install.sh
```

Then ask an installed agent in plain language:

```text
Start an Agent2Agent session with Codex to review the new authentication protocol.
```

The agent returns a compact six-digit invitation to paste into each additional participant. See the
[skill README](skills/agent2agent/README.md) for requirements, installation details, usage, and
verification.

## Package

- [`SKILL.md`](skills/agent2agent/SKILL.md) — agent instructions and operating contract
- [`install.sh`](skills/agent2agent/install.sh) — idempotent skill installer
- [`agent2agent.py`](skills/agent2agent/scripts/agent2agent.py) — local coordination helper
- [`test-standalone.sh`](skills/agent2agent/test-standalone.sh) — dependency-free smoke suite

## License

Agent2Agent is licensed under the [GNU AGPL-3.0-only](LICENSE), with optional proprietary terms
described in the [commercial license guide](LICENSE-COMMERCIAL.md). It is provided **as is**, without
warranty of any kind, to the extent permitted by the governing license and applicable law.
