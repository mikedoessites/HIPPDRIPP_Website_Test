Simple frontend scaffold and CLAUDE rules added by the assistant.

Files added:
- CLAUDE.md
- index.html
- serve.mjs
- screenshot.mjs

Run `node serve.mjs` then `node screenshot.mjs http://localhost:3000` to capture a screenshot.
# WAT (Workflows, Agents, Tools) skeleton

This repository contains a minimal skeleton for the WAT framework.

Quick start

1. Install Python dependencies (example):

```bash
pip install requests beautifulsoup4
```

2. Copy `.env.example` to `.env` and fill secrets if needed.

3. Run the example tool:

```bash
python tools/scrape_single_site.py --url https://example.com --out .tmp/example.json
```

Files of interest:
- `workflows/` — SOPs and workflows.
- `tools/` — Deterministic execution scripts.
- `.tmp/` — Temporary outputs.
