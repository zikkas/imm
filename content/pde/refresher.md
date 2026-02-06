+++
date = '2026-02-02T15:34:39+01:00'
draft = false
title = "Prerequisites and Refresher"
weight = 10
+++

## Mathematical Background

This course will depend on two concepts: unbounded linear operators on infinite-dimensional spaces and the semi-groups of operators. It will also be helpful to know how to solve ODEs and PDEs and why the solution exists and is unique. Some classical examples and their solution will be provided below (later).

### 1. $L^p$ Spaces

#### Key Concepts

- **Completeness:** $L^p$ is a Banach space (limits of Cauchy sequences stay in the space).
- **Norms & Convergence:**
  - Difference between pointwise convergence ($f_n(x) \to f(x)$) and norm convergence ($\|f_n - f\|_p \to 0$).
  - **Dominated Convergence Theorem:** When can you swap limits and integrals?
- **Inequalities:**
  - **Cauchy-Schwarz:** $|\langle f, g \rangle| \leq \|f\| \|g\|$.
  - **Hölder's Inequality:** $\left\lvert{fg}\right\rvert_1 \le \left\lvert{f}\right\rvert_p \left\lvert{g}\right\rvert_q$ where $\dfrac{1}{p} + \dfrac{1}{q} = 1$
- **Density of Smooth Functions:** Smooth functions ($C_c^\infty$) are dense in $L^p$.

### 2. Functional Analysis

#### Bounded vs. Unbounded

- **Bounded Operators:** Continuous linear maps.
- **Unbounded Operators:** Differential operators are not bounded. You must understand the concept of a **Domain** $D(A) \subset X$.

#### The Big Theorems

- **Hahn-Banach Theorem:** Guarantees we have enough dual elements to measure norms.
- **Closed Graph Theorem:** Used to prove regularity of solutions.
- **Uniform Boundedness Principle:** Used for convergence of approximation schemes.

#### Hilbert Spaces ($L^2$)

- Inner products and orthogonality.
- Riesz Representation Theorem (Every functional looks like an inner product).

---

### Recommended Review

#### Book: _Functional Analysis, Sobolev Spaces and Partial Differential Equations_ by Haïm Brezis

- **Chapter 1:** Hahn-Banach & Dual Spaces.
- **Chapter 4:** $L^p$ Spaces (Completeness, Separability).
- **Chapter 5:** Hilbert Spaces.

#### Quick Refresher Videos

Some will be provided later

#### Cheat Sheets

Some will be provided later

{{% notice tip "Contribute" %}}
**Missing anything or can it be improved?**
If you find anything that you think might be helpful/useful (sheets, resources, videos, etc..) please click the **Edit** button to add it here or tell me, I will gladly discuss it with you and add it.
{{% /notice %}}
