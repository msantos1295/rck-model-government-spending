# RCK Model with Government Spending

Extension of the Ramsey-Cass-Koopmans growth model incorporating government spending — coursework expanded into a short paper and published in a student journal.

**Published as:** [*RCK Model with Government Spending*](https://jhu-econ.github.io/jrafe/articles/2026/spring/rck-govt/), Johns Hopkins University's *Journal of Research in Applied Financial Economics (JRAFE)*, May 2026.

## Overview

The baseline Ramsey-Cass-Koopmans (RCK) model has no government. This project extends the framework to ask: if a social planner has a genuine preference for public goods (financed by lump-sum taxation), does that change the *dynamics* of the model — the saddle path, the speed of convergence to steady state — or only the *composition* of output at each point in time?

**Main result:** under separable CRRA preferences over private and public consumption with lump-sum financing, the answer is an *intertemporal neutrality* result. A planner's taste for public goods reshapes how output is split between private and public consumption at every date, but leaves the saddle path, the transition speed, and the steady-state capital stock completely undisturbed.

## What's in this repo

- `01_starter_baseline_rck.ipynb` — the baseline (no-government) RCK model, provided as course starter code: calibration, phase diagram, and transition dynamics via the shooting method.
- `rck_government_spending.ipynb` — the actual project: extending the model to include government spending, with its own calibration, phase diagram, transition dynamics, and welfare/optimal-composition analysis. Runs standalone (it recomputes the baseline steady state it compares against, rather than depending on the starter notebook).
- `rck_government_spending_slides.pptx` — slide summary of the results for presentation.
