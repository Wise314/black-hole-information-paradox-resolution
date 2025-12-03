# Reading Guide for Reviewers

**Status:** Pre-print, not yet peer reviewed  
**Last Updated:** December 3, 2025

---

## Overview

This paper argues that Hawking's equations (1975) mathematically exclude linear information transfer—the hidden assumption underlying the AMPS firewall paradox. The resolution requires no new physics, only correction of a premise that contradicts established physics.

Section 2.3 explicitly distinguishes mass, entropy, and information. The empirical validation is supporting evidence; the core argument is mathematical constraint elimination.

This guide addresses common questions; the arguments themselves are in the paper.

---

## IMPORTANT: How to Use This Guide

This guide anticipates objections that reviewers typically raise. Each objection below has been addressed. 

**If you find yourself wanting to raise one of these objections, you have either:**
1. Not read this guide carefully, or
2. Found the answer unconvincing—in which case, engage with the answer rather than restating the question.

The guide separates **Closed Issues** (addressed in the paper or guide) from **Open Issues** (legitimate areas for peer review). Do not re-raise closed issues without engaging with the provided answer.

---

## Key Structural Points

**Acceleration Constraint:** Hawking radiation gives dM/dt ∝ -1/M². Linear, logarithmic, quadratic, and exponential transfer functions produce constant or decelerating rates. Only power laws with α < 1 satisfy the required divergence as M→0.

**Why |dI_rad/dI| Must Diverge (Not Just |dI_rad/dt|):** This is central. Both linear and √ dampening give |dI_rad/dt| → ∞ (because |dI/dt| already diverges). So why must |dI_rad/dI| itself diverge?

The Page curve requires back-loading: more information remains at any given mass fraction than linear transfer predicts. Back-loading requires remaining information I_hole ∝ (M/M₀)^α with α < 1. If α < 1, then |dI_rad/dI| ∝ I^(α-1) → ∞. Linear transfer (α = 1) gives uniform information-per-mass, contradicting Page. This is why the constraint applies to |dI_rad/dI|, not just |dI_rad/dt|.

**Why I = M/M₀ (Not S/S₀ = M²/M₀²):** Information capacity is bounded by horizon area (holographic principle). Horizon area is determined by mass. Therefore information dynamics are constrained by mass dynamics. This is derived from the holographic principle, not assumed. See Section 6.2.

**Selection of α = 1/2:** Among power laws with α < 1, the value 1/2 is selected by Page curve timing (29.3% released at half-mass), holographic dimensional reduction, and cross-domain empirical validation. Three independent derivations converge.

**AMPS Resolution:** At the aggregate level, √ dampening means only 29.3% of information has escaped at Page time, not 50%. At the mode-by-mode level, each late Hawking quantum carries less of the unitarity burden, so the entanglement between late quanta and early radiation need not be maximal. The monogamy threshold is never reached. AMPS is dissolved—the paradox's premise was wrong.

**Geometric Origin:** The connection to empirical systems (bearings, neural networks, power grids, turbofans, seismic faults) is geometric, not analogical. All encode information in 3D bulk accessed through 2D measurement surfaces. When bulk dimensionality exceeds boundary dimensionality, √ scaling emerges from dimensional reduction.

**Empirical Validation:** Parameters α = 0.1 and Φ_c ≈ 0.25 were set once and applied across 27 systems in 5 domains with 100% predictive accuracy, including four real-world catastrophic events from pre-event data. This supports the framework but is not the core argument.

**Falsifiable Predictions:** Five numerical predictions testable in analog black hole experiments within 2-3 years. Strongest discriminator: information transfer rate acceleration (14.4σ separation from linear model).

---

## Known Errata

**Section 6.2 Notation:** The paper now contains the correct formula:

**I_accessible = √I = (S_BH/S₀)^(1/4)**

This was corrected from an earlier version that incorrectly stated I_accessible = √(S_BH/S₀).

---

## Closed Issues (Do Not Re-Raise Without Engaging With the Answer)

The following objections have been addressed. If you raise them without engaging with the answers below, you have not read this guide carefully.

**Q: "The paper conflates mass with information."**  
A: No. Section 2.3 defines I = M/M₀ (identity) as distinct from S ∝ M² (entropy). Section 6.2 derives their relationship. The connection is geometric (holographic principle), not assumed.

**Q: "Why must |dI_rad/dI| diverge rather than just |dI_rad/dt|?"**  
A: The Page curve requires back-loading. Back-loading requires α < 1. α < 1 gives |dI_rad/dI| → ∞. See "Key Structural Points" above for full derivation.

**Q: "Why should I = M/M₀ inherit Hawking's acceleration constraint?"**  
A: Because information capacity is bounded by horizon area (holographic principle), and horizon area is determined by mass. The relationship is derived, not assumed.

**Q: "The AMPS resolution only addresses aggregate flow, not mode-by-mode entanglement."**  
A: The aggregate argument is explicit. The mode-by-mode argument is implicit: per-quantum entanglement burden depends on total information distribution, which √ dampening changes. This is acknowledged as an area where the paper could be more explicit—see Open Issues.

**Q: "Is α = 1/2 arbitrary?"**  
A: No. The acceleration constraint eliminates α ≥ 1. Page curve timing, holographic geometry, and empirical validation independently select 1/2. Three independent derivations converge.

**Q: "Is the empirical validation the main argument?"**  
A: No. It is supporting evidence. The theoretical derivation in Section 2 depends only on Hawking's equations and logic. The empirics could be wrong and the theoretical argument would still stand.

**Q: "The Page curve tracks entanglement entropy, but I_rad tracks information content—aren't these different?"**  
A: Yes, they measure different aspects of the same physical state. The paper acknowledges this in Section 4.4. The connection is that both require back-loading, which selects α < 1 and specifically α = 1/2.

---

## Open Issues (Legitimate Areas for Peer Review)

The following are genuine questions for peer review and further development:

- The mode-by-mode AMPS argument could be made more explicit in the paper itself.
- The empirical methodology (how α = 0.1 and Φ_c ≈ 0.25 were determined, prospective vs retrospective prediction) warrants detailed documentation.
- The holographic derivation of √ scaling from dimensional reduction could be expanded mathematically.
- Larger sample sizes across AI and electrical domains would strengthen statistical confidence.

These are areas for strengthening, not refutation of the core argument.

---

## Document History

This guide was developed through adversarial dialogue with AI systems to identify likely objections before peer review. The dialogue surfaced:

1. The Section 6.2 notational error (now corrected)
2. The need to justify I = M/M₀ as the correct variable
3. The |dI_rad/dI| vs |dI_rad/dt| distinction
4. The implicit mode-by-mode AMPS argument

All substantive objections were either answered (Closed Issues) or identified as legitimate areas for future work (Open Issues).
