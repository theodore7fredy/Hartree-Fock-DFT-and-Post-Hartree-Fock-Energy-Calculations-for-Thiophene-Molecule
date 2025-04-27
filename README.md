# Hartree-Fock-DFT-and-Post-Hartree-Fock-Energy-Calculations-for-Thiophene-Molecule
 This repository provides quantum chemistry calculations for the **thiophene molecule** using **Hartree-Fock (HF)**, **Density Functional Theory (DFT)**, and **post-Hartree-Fock methods**. The project leverages **RDKit** for molecular structure generation and **PySCF** for quantum chemistry computations.

---

## Overview

Thiophene is an aromatic heterocyclic compound commonly used as a benchmark system in computational chemistry. This project focuses on:

- Generating the 2D structure of thiophene using **RDKit**.
- Computing electronic energies using **HF**, **DFT** (with selected functionals), and **post-Hartree-Fock methods** (e.g., MP2, CCSD).
- Exploring the impact of basis sets (e.g., STO-3G, 6-31G, cc-pVDZ, etc.) on the calculated energies.

The code enables comparisons between methods, providing insights into the accuracy and computational cost of different quantum chemistry approaches.

---

## Prerequisites

To run this project, ensure you have the following dependencies installed:

- **Python** (>=3.10)
- **RDKit** (>=2023.03)
- **PySCF** (>=2.2)
- Additional Python libraries:
  - NumPy
  - Pandas
  - Py3Dmol

---
