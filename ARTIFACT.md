# Artifact Guide

Build (Lean):
- Install Lean 4 and Mathlib (per standard instructions).
- lake build  # if a Lake package is present; otherwise open the Lean file in an editor for on‑demand elaboration.

Key lemma anchors cited in the paper:
- Constants.phi_fixed_point, Constants.fixed_point_unique_pos, Constants.delta_gap
- Constants.tau_rec, Constants.RSUnits.lambda_rec, Constants.RSUnits.lambda_rec_pi_eq
- ClassicalBridge.gaugeClass_eq_of_same_delta_basepoint (T4 uniqueness up to constant)
- Cost.Jlog, T5_EL_equiv_general (Euler–Lagrange on the log axis)
- Spectra.mass law scaffolding and zpow ratio lemmas
