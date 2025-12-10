# Technical Notes

**Last Updated:** December 3, 2025

---

## Summary

This paper derives that Hawking radiation dynamics (dM/dt ∝ -1/M²) require information transfer to follow √ dampening (I_accessible = √I). The derivation uses constraint elimination: seven candidate functional forms are tested against the acceleration requirement, and only √ survives.

The resolution of the information paradox follows as a consequence. Linear information transfer—the implicit assumption in AMPS—contradicts Hawking's equations. Correcting this assumption dissolves the firewall paradox.

---

## Key Technical Points

**Acceleration Constraint:** Hawking radiation gives dM/dt ∝ -1/M². Information transfer functions must be compatible with this. Linear, logarithmic, quadratic, and exponential forms produce constant or decelerating rates. Only power laws with α < 1 satisfy the required divergence as M→0.

**Why |dI_rad/dI| Diverges:** Both linear and √ dampening give |dI_rad/dt| → ∞ as M→0 (because |dI/dt| already diverges). The additional constraint comes from the Page curve, which requires back-loading: more information remains in the hole at any given mass fraction than linear transfer predicts. 

Back-loading requires I_hole ∝ (M/M₀)^α with α < 1. This gives |dI_rad/dI| ∝ I^(α-1) → ∞. Linear transfer (α = 1) produces uniform information-per-mass, contradicting Page's unitarity requirement.

**Why I = M/M₀:** The paper defines normalized identity I = M/M₀, distinct from Bekenstein-Hawking entropy S ∝ M². The relationship is derived from the holographic principle: information capacity is bounded by horizon area, horizon area is determined by mass, therefore information dynamics are constrained by mass dynamics.

**Selection of α = 1/2:** Among power laws with α < 1, the value 1/2 is selected by three independent constraints: Page curve timing (29.3% released at half-mass), holographic dimensional reduction, and cross-domain empirical validation.

**AMPS Resolution:** With √ dampening, only 29.3% of information has escaped at Page time (not 50%). The entanglement between late radiation and early radiation need not be maximal. The monogamy threshold required for firewall formation is never reached.

---

## Clarifications

**On mass vs. information:** Section 2.3 explicitly distinguishes I = M/M₀ (identity) from S ∝ M² (entropy). Section 6.2 derives their relationship: I_accessible = √I = (S_BH/S₀)^(1/4).

**On the acceleration constraint scope:** The constraint applies to |dI_rad/dI| because the Page curve requires back-loading. This is distinct from |dI_rad/dt|, which diverges for all models.

**On the AMPS argument:** The paper's AMPS resolution operates at the aggregate level explicitly. The mode-by-mode implication (reduced per-quantum entanglement burden) follows from the changed information distribution but could be developed more explicitly.

**On empirical validation:** The cross-domain validation (bearings, neural networks, power grids, turbofans, seismic systems) is supporting evidence. The theoretical derivation in Section 2 stands independently of the empirics.

---

## Areas for Future Development

- More explicit derivation of the mode-by-mode AMPS argument
- Expanded mathematical treatment of holographic dimensional reduction
- Detailed documentation of empirical methodology
- Extension to Kerr and Reissner-Nordström geometries

---

## Errata

**Section 6.2:** The paper contains the corrected formula:

I_accessible = √I = (S_BH/S₀)^(1/4)

An earlier draft incorrectly stated I_accessible = √(S_BH/S₀).

---

## License

© 2025 Shawn Barnicle. This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
