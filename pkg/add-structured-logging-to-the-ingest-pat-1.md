# Add structured logging to the ingest path

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #1 of 3 on branch `pr/20260811-121032-1-add-structured-logging-to-the-ingest-pat`.
