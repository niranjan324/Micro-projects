# Micro-projects
# 24BSE1211-PDE-MicroProject-Group-12-.
## 👥 Team Members & Roles — Group 12

| # | Name | Roll No. | Role | Key Responsibilities |
|---|------|----------|------|----------------------|
| 1 | Nesin Christy Shaji | [50.] | **Group Leader / Theoretical Lead** | Led the mathematical derivation (separation of variables, eigenvalue problem, boundary condition analysis); created and manages the GitHub repository; compiled the final Phase 1 LaTeX report |
| 2 | Niranjan A | [51.] | **Fourier Analysis & Proofs** | Derived the Fourier cosine coefficients for the step-function initial condition; wrote the formal proof of higher-frequency decay (Proposition & Lemma) |
| 3 | Nissi Sara Jacob | [52.] | **Computational Lead / Simulation Developer** | Implemented the truncated Fourier-series solution in Python (NumPy); wrote the core `I_xt()` simulation function and convergence checks |
| 4 | Anjana P J | [14.] | **Visualization & Data Analysis** | Built all Matplotlib visualizations (edge diffusion plot, low-pass spectrum plot, Gibbs phenomenon convergence plot); interpreted numerical results |
| 5 | Basim Kannadikkal | [19.] | **Documentation & QA** | Wrote markdown documentation/report narrative for the Colab notebook; proofread the LaTeX report; verified code reproducibility and managed final GitHub submission (commits, README) |

---

### Contribution Breakdown
- **Theoretical derivation (Phase 1):** Members 1, 2
- **Computational implementation (Phase 2):** Members 3, 4
- **Documentation, GitHub & final integration:** Members 1, 5

*All members contributed to discussions, review, and debugging across both phases.

## Project Summary

 1D Image Blurring and Restoration (The Heat Equation)

This project models pixel-intensity diffusion along a 1D medical-imaging 
scan line using the heat equation. We derive a closed-form Fourier cosine 
series solution via separation of variables, mathematically prove that 
higher spatial frequencies decay faster than lower ones, and use this 
result to simulate how a sharp clinical edge progressively blurs over time. 
Phase 1 covers the theoretical derivation (LaTeX report); Phase 2 
implements and visualizes the simulation in Python.
