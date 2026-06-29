# Quantum Simulation of the Two-Site Isotropic Heisenberg Model via QPE

This repository contains the complete implementation and simulation framework for resolving the energy eigenvalues of a two-site isotropic Heisenberg model using **Quantum Phase Estimation (QPE)** and **Phase Kickback** inside IBM's Qiskit environment.

## 📌 Project Overview
Classical exact numerical diagonalization scales exponentially as $2^N$. This project demonstrates how digital quantum simulators can native-map physical interaction terms ($X\otimes X$, $Y\otimes Y$, $Z\otimes Z$) without Trotterization constraints, because the isotropic components commute pairwise.

### Key Results
* **Singlet Ground State ($E_0 = -3J$):** Decoded to phase `0.2500` ($\approx 4.7\%$ discretization error using a 4-bit counting register).
* **Triplet Excited States ($E_1, E_2, E_3 = +1J$):** Confirmed threefold physical degeneracy via a convergent peak at phase `0.9375` (wrapped to `-0.0625`).

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/laith-alissa/Quantum-Heisenberg-QPE.git](https://github.com/laith-alissa/Quantum-Heisenberg-QPE.git)
   cd Quantum-Heisenberg-QPE
   
2. Install the dependencies
   ```bash
   pip install -r requirements.txt
   
3. Run the main simulation script:
    ```bash
   python heisenberg_qpe.ipynb


Another approach is to use the inserted notebook directly rather that setting up the environment.
