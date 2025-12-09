# Methods Overview

This directory defines the structural methodology used to test bounded
integration dynamics in cosmological systems.

The goal is to examine when large-scale cosmological integration measures
can be described by a bounded, monotonic logistic form and when this
description fails. No new physical cosmology model is introduced. All work
is compatibility-based and relies on standard ΛCDM and related frameworks.

The core integration variable is a derived scalar Φ(t), representing an
integrated cosmological quantity such as cumulative structure growth,
integrated correlation amplitude, or other normalized large-scale
summary statistics.

The logistic form under consideration is:

> dΦ/dt = r · λ · γ · Φ · (1 − Φ / Φ_max)

where

- **Φ(t)** is the derived integration measure,
- **r** is a time-scale parameter,
- **λ** is an external or background driver (e.g., expansion rate,
  matter content, or background conditions),
- **γ** is an internal coherence factor (e.g., clustering efficiency or
  structure-formation coherence),
- **Φ_max** is a structural upper bound implied by the chosen measure.

These parameters are treated as abstract scalars. They are not assumed to
be fundamental constants of nature and are not used to modify standard
cosmological equations.

Other files in this directory specify:

- the precise definitions of Φ for different cosmological regimes
  (`integration_measures.md`),
- the regimes where bounded logistic behavior is and is not expected
  (`regime_definitions.md`),
- the structural comparison between bounded logistic, linear, and other
  growth models (`model_comparison.md`).
