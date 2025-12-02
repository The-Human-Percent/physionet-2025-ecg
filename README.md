# PhysioNet 2025 ECG Digitization Challenge

Reconstruct digital ECG signals from paper ECG images for the PhysioNet/Computing in Cardiology Challenge 2025.

## Competition

- **URL**: https://www.kaggle.com/competitions/physionet-ecg-image-digitization/overview
- **Deadline**: 2026-01-22
- **Organization**: BioML Labs

## Team

| Role | Person | Responsibilities |
|------|--------|------------------|
| CEO | Dan | Infrastructure, compute, pipelines |
| CDO | Jess | Scientific validation, signal morphology |

## CEO Directives

1. **Hello World Mandate** - Submit valid model by Week 1
2. **Data Leakage Firewall** - CDO curates Golden Holdout
3. **Time-Box Rule** - Infrastructure capped at Week 2
4. **Compute Reality Audit** - Benchmark on Day 1

## Project Structure

```
physionet-2025-ecg/
├── docs/
│   ├── papers/          # Research papers
│   ├── experiments/     # Experiment notes
│   └── submissions/     # Submission artifacts
├── src/
│   ├── models/          # Model implementations
│   └── data/            # Data processing
├── tests/               # Test suite
├── project.yaml         # Project configuration
└── rsm-workflow-status.yaml  # Workflow tracking
```

## Quick Start

```bash
# Navigate to project
cd projects/bioml-labs/physionet-2025-ecg

# Start Claude Code
claude

# Invoke Competition Coordinator
/bmad:rsm:agents:competition-coordinator
```

## Integrations

- **Forgejo**: https://forgejo.hp.studio/BIOMLLABS/physionet-2025-ecg
- **Outline**: BioML Labs collection
- **Plane**: ECGDC project
- **Archon**: Project tracking

## License

Private - BioML Labs
