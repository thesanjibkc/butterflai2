> **Submission:** `03_latent_belt.ipynb` (Tasks 20–31) + `vocal_handoff.md`.  
> **AI assistance:** task code was written with help from ChatGPT and Claude (Claude provided Task 20 and most of Task 21). Details are in the session notes of `vocal_handoff.md`.

# Week 03 — From rate to magnetic field, and from 1D to 2D

**Phase A — Classical**

> Can a latent magnetic belt with a buoyancy threshold explain the emergence rate and the butterfly wing?

## Concepts

- The latent belt B(s) and the threshold emission Λ = c · softplus(B − B_crit)^α
- The **gauge** argument: why the emission must be fixed by physics before B means anything
- Fixing units with B_crit = 1: amplitude becomes 'multiples of critical'
- What a threshold predicts: sharp cycle onset from a smooth field; overlapping cycles that stay below threshold
- Extending to latitude: B(λ, s) as a drifting Gaussian belt, and 2D quadrature on a fixed mesh
- Pooling shapes across hemispheric cycles

## Deliverable

A 2D latent-belt model fitted to the butterfly diagram, compared against a direct-rate model on held-out likelihood.

## Notes

- Densest week of the program. Initialization of the threshold model is provided as given code: if B starts entirely below B_crit, gradients vanish.

## Notebook

_Released at the start of the week._ Task numbering continues from the previous week.
