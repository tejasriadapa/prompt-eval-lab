# Prompt Eval Lab

A lightweight prompt engineering + evaluation harness for LLM applications.

## Why this matters (AI Software Engineer roles)
- Builds evaluation datasets (JSONL)
- Runs repeatable experiments
- Tracks prompt quality requirements ("must include" checks)

## Repo structure
- `prompts/` - evaluation sets (JSONL)
- `src/` - scripts to run evaluations
- `data/` - reserved for datasets (local only)

## Quick start
```bash
pip install -r requirements.txt
python src/run_eval.py
