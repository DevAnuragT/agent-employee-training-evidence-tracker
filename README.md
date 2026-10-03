# Employee Training Evidence Tracker

Check role training records against required courses and expiry dates.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-employee-training-evidence-tracker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
