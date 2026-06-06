## NIFTY Options IV Surface Reconstruction
Predicting missing Implied Volatility values across the NIFTY50 options chain using surface dynamics, smile structure, and term decay.

## File Guide

### `final_IVsurface_reconstruction.ipynb`

Final competition submission notebook.

Contains:

* Data exploration
* Key observations
* Final reconstruction methodology
* Submission generation pipeline

---

### `ivsurface_complete_trials_detailed.ipynb`

Research and experimentation notebook.

Contains:

* Intermediate approaches
* Model tuning
* Failed experiments
* Comparison of different reconstruction methods
* Development process leading to the final solution

---

### `dataset.csv`

Competition dataset used for volatility surface reconstruction.

---

## Project Overview

This project focuses on reconstructing missing implied volatility (IV) values for NIFTY option contracts.

The objective is to recover missing IV observations while preserving realistic volatility smile behaviour across strikes and timestamps.

The final solution uses:

* Log-moneyness transformation
* ATM-weighted polynomial smile fitting
* Independent CE/PE smile reconstruction
* Linear-dominant edge extrapolation
