# Data Sync Service API — DITA starter kit

This folder contains a small, interview-ready DITA documentation set for a fictional **Data Sync Service API**
(ETL-style sync jobs and asynchronous runs).

## Folder layout

- `maps/` — entrypoint DITA map
- `concepts/` — overview, authentication, errors, pagination, and core concepts
- `tasks/` — step-by-step how-to topics (quickstart, create job, run job, backfill, replay)
- `reference/` — endpoint reference topics and resource schemas
- `assets/examples/` — example JSON payloads used by the docs

## Build/view options

If you have a DITA toolchain (DITA-OT), you can build HTML output with a command like:

```bash
dita -i maps/api-docs.ditamap -f html5 -o out
```

(Exact commands can vary depending on your DITA-OT installation.)

## Notes

- The API is intentionally fictional so you can control scope, ensure consistency, and demonstrate DITA structure.
- Endpoints follow a pragmatic REST design with idempotency support for writes.
