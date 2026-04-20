# Limitless Workflow

A Claude Code-first understanding machine powered by Oracle AI Database.

This workshop repo lets you:
- connect Oracle AI Database on OCI
- load starter topic packs
- run a smoke test
- launch XP Builder from Claude Code
- optionally inspect the Obsidian memory console

## What you need before the workshop

- an OCI Free Tier account
- an Oracle AI Database on OCI
- the downloaded wallet for that database
- Python 3.12+ (3.13 preferred, 3.14 works with warnings)
- Claude Code
- optionally Obsidian for the memory-console bonus path

## 5-minute quickstart

Use:
- `docs/quickstart.md`

Core command path:

```bash
python scripts/check_oracle_connection.py
python scripts/load_topics.py
python scripts/demo_smoke.py
```

Then open Claude Code in the repo root and run:

```text
/xp-builder agent-memory procedural-memory
```

## Advanced next step

```text
/xp-debrief agent-memory
/refresh-obsidian
/check-learning-state agent-memory
```

## Optional bonus

Open the `Limitless/` vault in Obsidian to inspect:
- dashboard
- topic notes
- Base
- Canvas
- graph
