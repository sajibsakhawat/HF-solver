# HF-solver – Hartree–Fock Equation Solver (Numerical Implementation)

This repository contains Python code and Jupyter notebooks for solving the **Hartree–Fock (HF) equations** for simple quantum systems.  
It provides a minimal, educational implementation of the self-consistent Hartree–Fock method, focusing on clarity, numerical stability, and visualization.

The project is suitable for physics  students learning:
- Many-body quantum mechanics  
- Mean-field approximations  
- Self-consistent field (SCF) methods  
- Numerical differential equation solving

---

## 📁 Repository Contents

### **`HF-solver.ipynb`**
Main Jupyter notebook implementing:
- The Hartree–Fock self-consistent loop
- Numerical solution of the Schrödinger-like HF equation
- Computation of orbitals, eigenvalues, and electron density
- Convergence checks
- Plots of wavefunctions & potentials



## 🧠 What the Code Does

The solver follows the standard Hartree–Fock procedure:

1. **Start with an initial guess** for the wavefunction or electron density  
2. **Construct the Hartree and/or exchange potentials**
3. **Solve the HF differential equation numerically**
4. **Compute a new electron density**
5. **Check convergence**
6. **Repeat until self-consistency is reached**

The notebook focuses on clarity and pedagogy rather than computational efficiency.

