# RCK Model with Government Spending

Extension of the Ramsey-Cass-Koopmans growth model incorporating government spending — coursework expanded into a short paper and published in a student journal.

**Published as:** [*RCK Model with Government Spending*](https://jhu-econ.github.io/jrafe/articles/2026/spring/rck-govt/), Johns Hopkins University's *Journal of Research in Applied Financial Economics (JRAFE)*, May 2026.

## Overview

The baseline Ramsey-Cass-Koopmans (RCK) model has no government. This project extends the framework to ask: if a social planner has a genuine preference for public goods (financed by lump-sum taxation), does that change the *dynamics* of the model — the saddle path, the speed of convergence to steady state — or only the *composition* of output at each point in time?

**Main result:** under separable CRRA preferences over private and public consumption with lump-sum financing, the answer is an *intertemporal neutrality* result. A planner's taste for public goods reshapes how output is split between private and public consumption at every date, but leaves the saddle path, the transition speed, and the steady-state capital stock completely undisturbed.

## What's in this repo

- `01_starter_baseline_rck.ipynb` — the baseline (no-government) RCK model, provided as course starter code: calibration, phase diagram, and transition dynamics via the shooting method.
- `rck_government_spending.ipynb` — the actual project: extending the model to include government spending, with its own calibration, phase diagram, transition dynamics, and welfare/optimal-composition analysis. Runs standalone (it recomputes the baseline steady state it compares against, rather than depending on the starter notebook).
- `rck_government_spending_slides.pptx` — slide summary of the results.

## Introduction (excerpt)

The Ramsey–Cass–Koopmans (RCK) model is the workhorse environment for analyzing how fiscal policy reshapes equilibrium outcomes when households save optimally. Its analytical value derives from a single modeling choice: rather than fix the saving rate exogenously, as in the Solow model, the RCK framework lets a forward-looking representative agent choose the path of consumption to maximize discounted CRRA utility under a neoclassical production technology.

The baseline RCK model abstracts from one feature no real economy lacks: a government. We establish a condition — separable preferences and lump-sum financing — under which utility-yielding government spending affects only the intratemporal allocation of resources between private and public consumption, leaving the intertemporal margin governing consumption growth unchanged. We refer to this as an intertemporal neutrality result for utility-yielding government spending.

## Conclusion (excerpt)

We derived what we called an intertemporal neutrality result. When preferences over private consumption and government spending are additively separable and both take the CRRA form with identical curvature, the planner's first-order conditions collapse to a simple static rule linking public and private consumption at every date. The steady-state capital stock remains unchanged across all values of the preference weight on public goods — what changes is purely intratemporal.

Several limitations point toward natural extensions: relaxing lump-sum taxation for distortionary taxes, relaxing separability between public and private goods, and endogenizing the preference weight itself within a political-economy framework.

## References

- Barro, R. J. (1988). Government spending in a simple model of endogenous growth (NBER Working Paper No. 2588).
- Carroll, C. D. and Lujan Solis, A. E. *A Gentle Introduction to Intertemporal Choice.* Johns Hopkins University.
- Romer, D. (2012). *Advanced Macroeconomics* (4th ed.). McGraw-Hill.
