# Contributing

Thank you for helping improve this textbook. Contributions are welcome in the
form of error reports, clarifications, and suggestions. Please read the
guidelines below before opening an issue or pull request.

---

## How to report an error

Use GitHub Issues with the appropriate template:

- **Factual / statistical error** — a test, theorem, formula, or citation that
  is incorrect or misattributed.
- **Notation inconsistency** — a symbol used differently across chapters.
- **Missing topic** — a method or concept that belongs in a specific chapter
  but is absent.
- **Typo / phrasing** — grammatical errors, unclear wording, broken
  cross-references.

When filing an issue, please include:
1. The chapter number and section (e.g., §14.2)
2. The specific claim or passage in question
3. A correction or reference supporting your suggestion

---

## Notation conventions

Consistency across 57 chapters requires strict notation rules. Please follow
these when suggesting edits or contributing content:

| Concept | Notation |
|---|---|
| Population parameter | Greek letters (μ, σ², β, θ) |
| Sample statistic | Roman letters with hat (x̄, s², β̂) |
| Random variable | uppercase italic (*X*, *Y*) |
| Observed value | lowercase italic (*x*, *y*) |
| Matrices | bold uppercase (**X**, **Σ**) |
| Vectors | bold lowercase (**x**, **β**) |
| Probability | P(·) |
| Expectation | E[·] |
| Variance | Var(·) |
| Distributions | N(μ, σ²), Bin(n, p), Pois(λ) |
| Estimators | denoted with hat: β̂, σ̂² |

---

## Pull request guidelines

1. Fork the repository and create a branch named for the change:
   `fix/ch14-fwl-theorem` or `add/ch15-tweedie-example`.
2. Keep changes scoped — one chapter or one conceptual fix per PR.
3. For `.docx` files, attach a summary of changes in the PR description
   since diffs on binary files are not human-readable.
4. Do not change chapter numbering or section headings without opening an
   issue first — cross-references throughout the book depend on them.

---

## What is out of scope

- Proofs that belong in a mathematical statistics text rather than an applied one
- Software documentation beyond the brief package references in each section
- Domain-specific regulatory or clinical standards (ICH E9, FDA guidance)

---

## Code of conduct

Be constructive and specific. Corrections are welcome; rewrites of entire
chapters are not. When in doubt, open an issue before writing a PR.
