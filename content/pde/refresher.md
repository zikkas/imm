+++
date = '2026-02-02T15:34:39+01:00'
draft = false
hidden = true
title = "Prerequisites and Refresher"
weight = 10
+++

# Mathematical Background

PDE is built on two pillars: the geometry of infinite-dimensional spaces (Functional Analysis) and the theory of integration (Lebesgue/$L^p$ spaces).

## 1. $L^p$ Spaces

### Key Concepts

- **Completeness:** Understand that $L^p$ is a Banach space (limits of Cauchy sequences stay in the space).
- **Norms & Convergence:**
  - Difference between pointwise convergence ($f_n(x) \to f(x)$) and norm convergence ($\|f_n - f\|_p \to 0$).
  - **Dominated Convergence Theorem:** When can you swap limits and integrals?
- **Inequalities:**
  - **Cauchy-Schwarz:** $|\langle f, g \rangle| \leq \|f\| \|g\|$ (Vital for $L^2$).
  - **Hölder's Inequality:** The generalization of Cauchy-Schwarz for $L^p$.
- **Density:** Knowing that smooth functions ($C_c^\infty$) are dense in $L^p$ (allows us to prove things for nice functions and extend by limits).

## 2. Functional Analysis

### Bounded vs. Unbounded

- **Bounded Operators:** Continuous linear maps (like matrices).
- **Unbounded Operators:** Differential operators (like $\Delta$ or $\partial_x$) are _not_ bounded. You must understand the concept of a **Domain** $D(A) \subset X$.

### The Big Theorems

- **Hahn-Banach Theorem:** Guarantees we have enough dual elements to measure norms.
- **Closed Graph Theorem:** Used to prove regularity of solutions.
- **Uniform Boundedness Principle:** Used for convergence of approximation schemes.

### Hilbert Spaces ($L^2$)

- Inner products and orthogonality.
- Riesz Representation Theorem (Every functional looks like an inner product).

---

## Recommended Review

### Book: _Functional Analysis, Sobolev Spaces and Partial Differential Equations_ by Haïm Brezis

- **Chapter 1:** Hahn-Banach & Dual Spaces.
- **Chapter 4:** $L^p$ Spaces (Completeness, Separability).
- **Chapter 5:** Hilbert Spaces.

### Quick Refresher Videos

Some will be provided later

### Cheat Sheets

Some will be provided later
