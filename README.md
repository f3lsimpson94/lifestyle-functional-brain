# lifestyle-functional-brain

Analysis repository for PhD Paper 1: diet patterns, cardiometabolic risk, and resting-state functional connectivity.

## What is in this repo (for now)
- Analysis scripts and helper functions (Python)
- Jupyter notebooks (later, if/when added)
- A small MATLAB folder for legacy steps (optional)

## What is NOT in this repo
- Any raw or participant-level data
- Derived datasets produced from sensitive inputs

## Working locally
This project expects data to live outside the repository. Create a local config file at:

config/paths.yaml

Use this template as a starting point:

config/paths.example.yaml

## Structure
- notebooks/     Notebook-based analysis workflow (added later)
- src/           Reusable helper functions for notebooks/scripts
- scripts/       Run scripts and utilities
- matlab/        Legacy MATLAB steps (kept contained)
- outputs/       Figures/tables (optional to track; finals only is recommended)
- data/          Present for structure only. Data should never be committed.

## Notes
This repository is designed to be readable and reproducible, while preventing accidental data uploads.
