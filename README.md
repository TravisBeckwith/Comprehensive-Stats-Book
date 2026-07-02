# Comprehensive Statistics
[![DOI](https://zenodo.org/badge/1287424895.svg)](https://doi.org/10.5281/zenodo.21139235)


**A Complete Textbook Outline and Categorized Methods Reference**

*From probability foundations and descriptive statistics through Bayesian inference, causal methods, time series, machine learning, and epidemiology.*

---

## Overview

This repository contains the master planning documents for **Comprehensive Statistics**, a structured, graduate-to-practitioner-level statistics textbook. The project consists of two companion documents:

| Document | Purpose |
|---|---|
| `stats_textbook_outline.docx` | Master topic inventory — 57 chapters across 17 parts |
| `statistical_tests_reference.docx` | Categorized quick-reference of 65 statistical test families |

The outline is a curriculum blueprint, not a finished text. Each chapter heading is a self-contained unit; each numbered section is a major heading; each bullet is a concept, technique, or tool requiring exposition, worked examples, exercises, and figures in the final book.

---

## **Textbook Structure**

### Part I — Foundations of Statistical Thinking
- Chapter 1 · The Nature of Statistics and Scientific Reasoning
- Chapter 2 · Probability Theory
- Chapter 3 · Probability Distributions
- Chapter 4 · Descriptive Statistics and Data Visualization

### Part II — Collecting Data: Sampling and Experimental Design
- Chapter 5 · Sampling Theory and Survey Methods
- Chapter 6 · Experimental Design

### Part III — Statistical Inference: Foundations
- Chapter 7 · Estimation Theory
- Chapter 8 · Hypothesis Testing: Foundations and Philosophy

### Part IV — Inference for Means and Proportions
- Chapter 9 · One-Sample and Two-Sample Inference
- Chapter 10 · Categorical Data Analysis
- Chapter 11 · Distribution Testing and Assumption Checking

### Part V — Comparing Multiple Groups: ANOVA and Extensions
- Chapter 12 · Analysis of Variance
- Chapter 13 · Multivariate Analysis of Variance

### Part VI — Regression and the Generalized Linear Model
- Chapter 14 · Simple and Multiple Linear Regression
- Chapter 15 · The Generalized Linear Model
- Chapter 16 · Regularized, Flexible, and Nonparametric Regression
- Chapter 17 · Mixed-Effects Models and Correlated Data

### Part VII — Correlation, Association, and Multivariate Methods
- Chapter 18 · Correlation and Measures of Association
- Chapter 19 · Dimension Reduction and Latent-Structure Methods
- Chapter 20 · Cluster Analysis
- Chapter 21 · Discriminant Analysis and Classification

### Part VIII — Structural Equation, Causal, and Mediation Models
- Chapter 22 · Structural Equation Modeling (SEM)
- Chapter 23 · Causal Inference

### Part IX — Survival Analysis and Longitudinal Methods
- Chapter 24 · Survival Analysis
- Chapter 25 · Longitudinal and Panel Data Analysis

### Part X — Time Series Analysis
- Chapter 26 · Time Series: Foundations and Classical Models
- Chapter 27 · Advanced Time Series and Forecasting

### Part XI — Bayesian Statistics
- Chapter 28 · Bayesian Inference
- Chapter 29 · Bayesian Computation and Applications

### Part XII — Resampling, Robust, and Non-parametric Methods
- Chapter 30 · Resampling Methods
- Chapter 31 · Robust Statistics
- Chapter 32 · Comprehensive Non-parametric Methods

### Part XIII — Specialized Topics and Domain Methods
- Chapter 33 · Missing Data
- Chapter 34 · Effect Sizes and Statistical Power
- Chapter 35 · Meta-Analysis and Research Synthesis
- Chapter 36 · Spatial Statistics
- Chapter 37 · Circular and Directional Statistics
- Chapter 38 · Extreme-Value Theory and Reliability
- Chapter 39 · Psychometrics and Item Response Theory
- Chapter 40 · Epidemiological Methods

### Part XIV — Machine Learning and Statistical Prediction
- Chapter 41 · Supervised Learning
- Chapter 42 · Unsupervised Learning and Representation

### Part XV — Data Transformation, Computation, and Workflow
- Chapter 43 · Data Transformations
- Chapter 44 · Computational Statistics and Simulation
- Chapter 45 · Reproducibility, Reporting, and Research Practice

### Part XVI — Appendices
- Appendix A · Mathematical Notation and Symbols
- Appendix B · Statistical Tables
- Appendix C · Probability Distribution Reference
- Appendix D · Test and Method Decision Guide
- Appendix E · Glossary
- Appendix F · Cross-Reference: Tests and Methods by Application

### Part XVII — Advanced Paradigms in Modern Data Science
- Chapter 46 · Functional Data Analysis (FDA)
- Chapter 47 · Compositional Data Analysis (CoDa)
- Chapter 48 · Topological Data Analysis (TDA)
- Chapter 49 · Joint Longitudinal–Survival Models
- Chapter 50 · Graphical Models and Causal Discovery
- Chapter 51 · Post-Selection and High-Dimensional Inference
- Chapter 52 · Conformal Prediction and Distribution-Free Uncertainty
- Chapter 53 · E-Values and Safe Anytime-Valid Inference
- Chapter 54 · Causal Machine Learning
- Chapter 55 · Bayesian Nonparametrics
- Chapter 56 · Simulation-Based Inference and Likelihood-Free Methods
- Chapter 57 · Dynamic Treatment Regimes and Reinforcement Learning

---

## Statistical Tests Reference

The companion reference document organizes **65 test families** into a three-column lookup table (method · purpose · notes/assumptions), covering:

- **Classical inference** — t-tests, ANOVA, chi-squared, proportion tests, correlation
- **Regression and GLMs** — OLS, logistic, Poisson, negative binomial, Gamma, Tweedie, mixed models
- **Non-parametric and resampling** — Mann-Whitney, Kruskal-Wallis, bootstrap, permutation tests
- **Survival analysis** — Kaplan-Meier, Cox PH, accelerated failure time, competing risks
- **Multivariate methods** — MANOVA, PCA, factor analysis, discriminant analysis, cluster analysis
- **Bayesian methods** — MCMC, posterior inference, Bayes factors, empirical Bayes
- **Causal inference** — propensity scores, instrumental variables, DiD, synthetic controls, causal forests
- **High-dimensional inference** — LASSO, ridge, elastic net, knockoffs, post-selection inference
- **Spatial and temporal methods** — spatial autocorrelation, variogram, ARIMA, state-space models
- **Epidemiological measures** — incidence, prevalence, relative risk, attributable fractions, DAGs
- **Modern frameworks** — conformal prediction, e-values, optimal transport, simulation-based inference
- **Foundational principles** — the Likelihood Principle, Sufficiency, Stein's Paradox, Berkson's Paradox

---

## Scope

**What this covers.** The outline aims to be inclusive rather than selective, spanning the inferential statistics tradition, the modeling tradition, the machine learning tradition, and key applied domains (epidemiology, psychometrics, spatial analysis, time series, reliability).

**Depth philosophy.** Foundational chapters (Parts I–III) are written at introductory depth with no assumed background. Later parts progressively assume earlier material. Appendices are reference-level, not tutorial.

**What is deliberately excluded.** Proofs that belong in a mathematical statistics text rather than an applied one; specialized software documentation; and domain-specific regulatory standards (ICH E9, FDA guidance). Deep learning architectures and spatial databases are included as topics but not developed in full.

---

## How to Use the Outline

> Start from the question, not the test. First identify the outcome type (continuous, count, binary, ordinal, time-to-event), the number of groups or predictors, and whether observations are independent or repeated. That combination points to one chapter family. Then check assumptions using the diagnostic tests in Chapters 11, 14.4, and 15.1, and switch to a robust, non-parametric, or resampling alternative if they are violated.

Cross-references are embedded throughout the outline (e.g., "also Chapter 20") to flag where the same topic appears from a different angle. **Appendix D** (Test and Method Decision Guide) and **Appendix F** (Cross-Reference by Application/Software) are designed as living documents updated as chapters are finalized.

---

## Files

```
├── stats_textbook_outline.docx          # Master 57-chapter topic inventory
├── statistical_tests_reference.docx     # 65-section categorized methods reference
└── README.md                            # This file
```

---

## Status

These documents are **outlines and planning materials** — a master topic inventory and a methods reference. The prose chapters, worked examples, exercises, and figures for the final text are in progress.
