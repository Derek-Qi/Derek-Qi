<div align="center">
  <img src="./assets/derekqi-banner.svg" alt="DQ monogram with a network motif representing research, engineering, and AI" width="100%" />
</div>

<h1 align="center">Derek Qi</h1>

<p align="center">
  Computer Science undergraduate at Liaoning Normal University<br />
  <a href="https://derekqi.com/">Personal website</a>
</p>

---

## About

I enjoy turning research questions into software that can be inspected, tested, and reproduced. My work brings together machine learning, scientific data, and systems engineering, with an emphasis on transparent evaluation and reliable implementation.

I also explore practical AI systems and agent-assisted developer workflows.

## Research interests

- Machine learning for scientific and materials data
- Uncertainty quantification and model reliability
- Human motion analysis and action quality assessment *(exploratory)*
- AI systems and developer tooling

## Selected projects

### [MaterialSense](https://github.com/Derek-Qi/MaterialSense-public)

A research and educational project for predicting concrete compressive strength from ingredient quantities and curing age.

- Group-aware evaluation on the UCI Concrete Compressive Strength dataset (1,030 observations).
- Ten recorded grouped resplits: **MAE 4.157 ± 0.609 MPa** and **RMSE 5.641 ± 0.788 MPa**. These describe split-to-split variability, not independent material experiments or confidence intervals.
- Includes prediction intervals, novelty warnings, ablation analysis, and documented failure cases.
- Research/education only: it is not validated for engineering design, and cross-source assessment remains exploratory rather than formal harmonized external validation.

### [FAT12 Disk Lab](https://github.com/Derek-Qi/FAT12-Disk-Lab)

A byte-level workbench for inspecting and safely modifying FAT12 disk images.

- Implements allocation analysis, deterministic compaction previews, hash-bound write plans, snapshot-protected persistence, and recovery.
- Uses a Python filesystem engine with a local React interface.
- Fixed-seed experiments reduced file extents from **33 to 23** in two ordinary layouts while preserving file-content and metadata hashes. These are layout-preservation results, not disk-speed benchmarks.

## How I work

- Reproducible experiments over one-off demos
- Evidence and explicit limitations over inflated claims
- Tests, verification, and inspectable implementation
- Safe defaults and recoverable operations

## Current explorations

I am exploring temporal human-pose representations for action quality assessment, alongside reusable AI-agent workflows for more reliable software development.

## Working stack

**Python** · **React** · **Streamlit** · **Git** · **GitHub Actions**
