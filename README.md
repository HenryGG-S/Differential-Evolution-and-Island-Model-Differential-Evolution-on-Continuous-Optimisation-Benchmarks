# Differential-Evolution-and-Island-Model-Differential-Evolution-on-Continuous-Optimisation-Benchmarks
An Experimental Study of Differential Evolution and Island-Model Differential Evolution on Continuous Optimisation Benchmarks

---
## Core research questions
- Does Differential Evolution outperform random search on standard continuous optimisation benchmarks under equal evaluation budgets?
- How sensitive is DE to its core parameters on these benchmarks?
- Does an island-model DE improve performance or robustness relative to vanilla DE?

---
## Exact benchmark suite
- Sphere
- Rosenbrock
- Rastrigin
- Ackley
- Griewank

Why this set works:
- Sphere is a simple unimodal baseline
- Rosenbrock gives a curved valley / conditioning challenge
- Rastrigin and Ackley give multimodality
- Griewank gives another nontrivial landscape with many local structures

---
## Dimensions
- 10D
- 30D
