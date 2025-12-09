# Cosmological Regime Definitions

This document specifies the cosmological regimes where bounded,
logistic-style integration for Φ(t) is expected to be structurally
compatible, and where it is expected to fail.

The logistic form considered is:

> dΦ/dt = r · λ · γ · Φ · (1 − Φ / Φ_max)

Compatibility here means that Φ(t) can reasonably be modeled as:

- monotonic over the time window studied,
- bounded and saturating,
- driven by coupled external (λ) and internal (γ) factors.

## 1. Inflationary and Very Early Universe (❌ Not Compatible)

Inflation and the earliest epochs are dominated by physics beyond the
scope of this project. Rapid exponential expansion, quantum fluctuations,
and reheating dynamics do not naturally produce a bounded, monotonic Φ(t)
of the type defined here.

- Integration variables are poorly defined on these scales.
- Any apparent saturation is model-dependent and not structurally robust.

Therefore, these epochs are **excluded** from logistic-style analysis.

## 2. Radiation-Dominated Era (❌ Not Compatible)

During radiation domination:

- the expansion is set primarily by relativistic species,
- structure growth is strongly suppressed,
- sound horizons and oscillations dominate observables.

These conditions introduce oscillatory and non-monotonic behavior in many
candidate Φ(t) measures (e.g., baryon acoustic oscillations). Logistic-type
bounded integration is **not** assumed to be appropriate here.

## 3. Matter-Dominated Era (✅ Conditionally Compatible)

In the matter-dominated epoch:

- structure formation becomes efficient,
- halo mass functions and correlation functions grow in a relatively
  monotonic fashion over wide ranges of redshift,
- cumulative structure indicators often exhibit saturation behavior
  at late times.

For appropriately chosen Φ(t) (e.g., cumulative halo mass fraction over a
fixed mass range), logistic-style bounded integration can be a reasonable
structural approximation.

This regime is treated as **conditionally compatible**, subject to
explicit tests of monotonicity and saturation.

## 4. Dark-Energy–Dominated Era (✅ Structurally Compatible)

At low redshift, dark-energy domination slows further growth of structure.
Commonly used growth indicators:

- approach asymptotic values,
- exhibit clear diminishing returns in time.

Under these conditions, a bounded, saturating Φ(t) with a finite Φ_max is
structurally plausible. Here:

- **λ** reflects the combined influence of background expansion and
  matter content,
- **γ** reflects residual coherence in structure growth.

This regime is considered **structurally compatible** with logistic-style
bounded integration, again subject to empirical checks.

## 5. Nonlinear and Feedback-Dominated Small-Scale Regimes (⚠ Mixed)

On small scales, baryonic feedback, galaxy formation physics, and
environmental processes can produce:

- non-monotonic behavior,
- local over- and under-shooting,
- scale-dependent evolution.

Some derived Φ(t) measures may remain effectively bounded and monotonic,
while others will not. These regimes are treated as **mixed** and require
case-by-case evaluation.

## 6. Summary of Boundary Conditions

- Very early universe (inflation, reheating, pure radiation domination):
  **excluded**.
- Matter domination: **conditionally compatible** for carefully chosen Φ.
- Dark-energy domination: **structurally compatible** for large-scale Φ.
- Highly nonlinear small-scale regimes: **mixed**, require explicit checks.

These boundaries prevent over-extension of the logistic-style framework
and make the cosmology application explicitly falsifiable.
