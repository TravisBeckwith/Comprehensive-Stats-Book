# Changelog

All substantive revisions to the outline, reference document, and chapter
drafts are recorded here. Format follows [Keep a Changelog](https://keepachangelog.com).

---

## [Unreleased]

### Outline (`stats_textbook_outline.docx`)

#### Fixed
- Header corrected: 45 chapters → 57 chapters · 16 parts → 17 parts
- §57.5 cross-reference corrected: "Chapter 58" → Section 6.7
  (sequential and adaptive designs)

#### Added
- Part XVII: Advanced Paradigms in Modern Data Science (Chapters 46–57)
  relocated from after Appendices into a properly named part
- §2.5 — exchangeability and de Finetti's representation theorem
- §2.8 — Le Cam's theorem; total variation, KL, Hellinger distances;
  Pinsker's inequality
- §9.4 — Agresti-Caffo confidence interval for difference of two proportions
- §10.3 — Mantel-Haenszel pooled odds-ratio estimator; Simpson's paradox
  resolution via stratification (cross-ref Chapter 45)
- §14.2 — Frisch-Waugh-Lovell theorem
- §14.6 — New subsection: Measurement error in covariates (classical vs.
  Berkson error, attenuation bias, regression calibration, SIMEX,
  errors-in-variables regression)
- §15.3 — Conditional (matched) logistic regression; continuation-ratio model
- §15.5 — Tweedie (compound Poisson-gamma) regression
- §22.4 — Causal mediation: natural direct and indirect effects (VanderWeele)
- §23.3 — Targeted maximum likelihood estimation (TMLE)
- §24.3 — Harrell's C-index and calibration for survival models
- §30.1 — Block and sieve bootstrap for dependent (time-series) data
- §33.6 — New subsection: Sensitivity analysis under MNAR (pattern-mixture
  models, selection models, delta-adjustment, tipping-point analysis)
- §41.5 — Conformal prediction for distribution-free uncertainty quantification
- §51.5 — Concentration of measure
- §54.4 — Triple difference (DDD); Abadie (2005) semiparametric
  propensity-score-weighted DiD
- Scope Notes — acknowledgment of functional data analysis, network/graph
  models, Bayesian nonparametrics, and compositional data as out-of-scope
  branches

#### Changed
- §52.3 — CRC attribution corrected: Angelopoulos et al. (2022), not Bates
- §52.3 — RCPS attribution corrected: Bates et al. (2021); description updated

### Reference (`statistical_tests_reference.docx`)

#### Fixed
- §56 (X-learner) — Author name corrected: Kunzel → Künzel (Sören R. Künzel)
- §52 (Knockoff filter) — Author name corrected: Candes → Candès (all four
  occurrences across §52, §53, §60)
- §53 (Jackknife+/CV+) — Co-author corrected: "Tibshirani & Tibshirani" →
  Barber, Candès, Ramdas & Tibshirani (2021)

#### Changed
- §1 — Proportion z-test relationship reworded: "special case" → "analogous to"
  (the proportion test has a mean-dependent variance; it is not a special case)
- §2 (Brunner-Munzel) — Relative effect now shows the full tie term:
  P(X<Y) + ½P(X=Y) ≠ ½
- §6 (Vuong test) — Caveat added: ZIP vs. Poisson non-nestedness dispute
- §20 (Type III/IV errors) — Note added: labels are not standardized;
  Kimball's "right answer to wrong question" is an alternative usage
- §29 (Geary's C) — Corrected from "local contrasts" to global statistic
  built from squared differences of neighbors

#### Added
- §3 — Rao-Scott corrected chi-squared for complex survey designs
- §5 — Conditional (matched) logistic regression
- §5 — Errors-in-variables / regression calibration
- §13 — Harrell's C-index (concordance statistic for survival models)
- §18 — Block / sieve bootstrap for dependent data
- §27 — Causal mediation: natural direct and indirect effects (VanderWeele)
- §32 — Cross-reference to Stein's Paradox (Section 66)
- §38 — Cross-reference to Berkson's Paradox (Section 66)
- §46 — Cross-reference to Law of Truly Large Numbers (Section 66)
- §66 (new) — Foundational principles and paradoxes of inference:
  interpretations of probability, Likelihood Principle, Sufficiency Principle,
  invariance/equivariance, Stein's Paradox, Berkson's Paradox,
  Law of Truly Large Numbers

---

## [0.1.0] — Initial outline and reference documents committed
