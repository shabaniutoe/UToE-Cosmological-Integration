# Cosmological Integration Measures

This document specifies how the abstract integration variable Φ(t) is
constructed in different cosmological contexts. Φ(t) is always a **derived
summary statistic**, not a replacement for the underlying cosmological
equations.

The general logistic form considered is:

> dΦ/dt = r · λ · γ · Φ · (1 − Φ / Φ_max)

with Φ constrained to 0 ≤ Φ ≤ Φ_max over the time interval of interest.

## 1. Large-Scale Structure Growth

For late-time matter-dominated and dark-energy–dominated epochs, Φ(t) can
be instantiated as a normalized cumulative structure-growth index:

- Φ(t) ∝ ∫₀ᵗ G(τ) dτ

where G(τ) is a dimensionless growth indicator such as:

- the linear growth factor normalized to unity at z = 0,
- a cumulative halo mass fraction above a fixed mass threshold,
- an integrated two-point correlation amplitude over a fixed comoving scale.

Here:

- **λ** corresponds to background expansion and matter content that
  drive gravitational instability,
- **γ** corresponds to the efficiency and coherence of structure
  formation (e.g., clustering coherence, feedback-regulated efficiency),
- **Φ_max** reflects saturation of structure on the scales probed by G.

## 2. Halo Mass Function Integration

Another compatible construction is a cumulative halo mass function:

- Φ(t) = ∫_{M_min}^{M_max} n(M, t) dM

where n(M, t) is the comoving number density of halos of mass M at
cosmic time t, optionally normalized to lie in [0, 1].

In this case:

- **λ** reflects the background cosmology controlling collapse timescales,
- **γ** reflects nonlinear clustering and baryonic feedback that modulate
  how efficiently mass assembles into halos,
- **Φ_max** is set by the asymptotic mass fraction in collapsed objects
  over the chosen mass range.

## 3. Integrated Correlation Measures

For some analyses, Φ(t) may represent cumulative correlation strength:

- Φ(t) = ∫_{r_min}^{r_max} ξ(r, t) W(r) dr

where ξ(r, t) is the two-point correlation function and W(r) is a fixed
weighting kernel over comoving scales of interest.

Here:

- **λ** encodes background expansion and matter content,
- **γ** encodes coherence of clustering and bias,
- **Φ_max** corresponds to a saturation level of large-scale correlations
  under the chosen normalization.

## 4. Quantities Excluded from Φ

The following are **not** used directly as Φ:

- the Hubble parameter H(t),
- the scale factor a(t),
- raw energy densities (ρ_m, ρ_Λ, ρ_r) without integration or
  normalization,
- early-universe quantities dominated by inflation or radiation.

These quantities can influence λ or γ but are not treated as integration
variables themselves.

## 5. Normalization and Interpretation

In all use cases:

- Φ(t) is normalized to [0, 1] when possible,
- Φ_max is interpreted as a structural upper bound implied by the
  chosen normalization and scale,
- λ and γ are abstract, scalar summaries of external and internal
  contributions; they are not used to modify the Einstein equations or
  the ΛCDM model.

This keeps the analysis strictly structural and avoids introducing new
fundamental cosmological dynamics.
