# OzCE-short
Noise and sensitivity modeling for an Australian, short‑baseline interferometer inspired by the Cosmic Explorer reference design.

Proposed layout for this repo:
- `ifo/` -- project-specific YAML files, including a `canonical/` subdir for copies to upstream `pygwinc` IFOs and a `variant/` subdir for derived detectors
- `notebooks/` -- Jupyter notebooks exploring parameter variations, sensitivity curves, and noise budgets (possibly each importing `pygwinc`)
- `scripts/` -- command-line Python scripts to generate automated plots (more like a placeholder for now)
- `env/` -- configuration files specifying dependencies (`pygwinc`, `finesse`,...)
- `docs/` -- project documentation
