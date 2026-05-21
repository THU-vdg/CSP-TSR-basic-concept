*Author:** Zizhen Li (李子臻)  
> **Date:** May 2026

## 📌 Project Overview
This repository contains a comprehensive set of academic study notes focusing on **Computational Singular Perturbation (CSP)** and **Tangential Stretching Rate (TSR)** methods. These methods are mathematically robust frameworks used to analyze combustion dynamics, reactive flow systems, and highly stiff Ordinary Differential Equations (ODEs) / Partial Differential Equations (PDEs).

The project systematically covers the decomposition of dynamic systems into tangent spaces, the separation of fast and slow manifolds, and the calculation of pivotal participation indexes to identify active modes and reaction pathways.

---

## 📖 Key Features & Theoretical Framework

### 1. Tangent Space Decomposition & Fast-Slow Separation
- Formulations for decomposing the vector field of chemical source terms into fast/slow subspaces using Right ($A$) and Left ($B$) basis vectors.
- Real/Complex eigenvalues, Jordan Canonical Forms, and their physical implications on system stability.

### 2. CSP Refinement Algorithm (Non-Linear Systems)
- Mathematical derivation of the two-step refinement process utilizing **Sylvester Equations**.
- Handling system non-linearities, coordinate rotations, and iterative block-diagonalization to reduce mode coupling cross-talk to $\mathcal{O}(\varepsilon)$.

### 3. Tangential Stretching Rate (TSR)
- The Rayleigh quotient definition of TSR in multi-dimensional state space.
- TSR state-space splitting: Active slow evolution vs. Depleted fast constraints.
- Extended TSR formulations incorporating transport-chemistry coupling for PDEs under large Damköhler ($\mathrm{Da}$) number assumptions.

### 4. Participation Indexes
- **TPI (Time-scale Participation Index):** Identifies reactions governing specific timescales.
- **API (Amplitude Participation Index):** Identifies reactions driving the amplitude of a specific mode.
- **S/FII (Slow/Fast Importance Index):** Evaluates the fractional contribution of fast vs. slow processes to state variable change rates.
- **TSR-PI:** Comprehensive index weighting mode dynamics to total tangential stretching.
