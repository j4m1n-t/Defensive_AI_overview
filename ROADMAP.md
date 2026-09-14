# Research Roadmap

## Phase 0 — Infrastructure specification

- Record CPU, RAM, GPU/VRAM, storage, NIC, and virtualization capabilities for both desktop/server-class machines.
- Determine sustainable VM allocations for target, attacker, and defender systems.
- Select the initial logging/telemetry stack.
- Establish isolated lab networking and administrative access paths.

## Phase 1 — Baseline laboratory

- Build fully patched Windows 11 target baseline.
- Build Windows attacker baseline, followed by Kali Linux.
- Build Ubuntu LTS defender baseline.
- Deploy centralized logging and telemetry services.
- Validate time synchronization and end-to-end event collection.

## Phase 2 — Local AI integration

- Benchmark candidate local models with Ollama against available hardware.
- Define attacker and defender harnesses.
- Measure inference latency, memory/VRAM use, token throughput, and task reliability.
- Establish deterministic experiment manifests where practical.

## Phase 3 — Controlled experiments

- Define repeatable defensive scenarios.
- Capture target state, attacker actions, defender actions, telemetry, timing, and outcomes.
- Run repeated trials to characterize variance.
- Preserve sufficient metadata to reproduce each trial.

## Phase 4 — Comparative testing

- Introduce Windows Server targets.
- Compare Windows and Kali attacker environments.
- Compare Ubuntu LTS and Red Hat-based defender environments.
- Compare local models and, where justified, frontier models under equivalent scenarios.

## Phase 5 — Research outputs

- Analyze quantitative and qualitative results.
- Produce technical report and research paper artifacts.
- Separate reproducible methodology/results from sensitive operational artifacts.
