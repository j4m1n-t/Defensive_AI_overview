# Experiments

Experiment definitions and metadata live here. Raw telemetry and sensitive artifacts should remain outside Git and be referenced by identifier or storage location.

## Minimum experiment record

Each run should identify:

- Experiment ID and date/time
- Research question / hypothesis
- Target baseline and snapshot
- Attacker OS, model, harness, prompt/config version
- Defender OS, model, harness, prompt/config version
- Logging stack and configuration version
- Network topology
- Start/end time
- Success/failure criteria
- Observed detections and defensive actions
- Resource usage and timing metrics
- Artifact/log references
- Analyst notes and anomalies

Use `experiment-template.md` as the starting point for new scenarios.
