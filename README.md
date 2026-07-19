# TRC V24 – Torsion Rebound Cosmology

**A 5D Einstein-Cartan Template for Dark Energy, S8, and a Sharp θ13 Test**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21444517.svg)](https://doi.org/10.5281/zenodo.21444517)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)

---

## Overview

This repository contains the complete code implementation for TRC V24, a geometrically-motivated unified framework that resolves the biggest empirical headaches of 2026 cosmology—S8, H0, and dynamic dark energy—and makes a single decisive, short-term prediction: θ13 ≈ 11-12°, testable by DUNE and Hyper-Kamiokande (2027-2028).

The framework derives all major phenomena from a single 5D Einstein-Cartan action with the Strange Quantum Medium (SQM) as the pre-geometric substrate.

---

## Key Results

| Sector | Status | Key Prediction |
|--------|--------|----------------|
| BAO | ✓ Passed | chi2/dof = 1.604 |
| S8 | ✓ Resolved | S8 = 0.775 (DES: 0.759±0.025; KiDS: 0.766±0.020) |
| H0 | ✓ Resolved | H0 = 70.13 km/s/Mpc |
| Dynamic Dark Energy | ✓ Predicted & Confirmed | wa ≈ +0.097 (DESI DR2 2026) |
| Neutrino Mixing | ✓ Passed | chi2 = 21.08 (6 parameters) |
| θ13 | ⚠ Predicted | 11-12° (4σ above current 8.5° global fit) |
| Σmν | ✓ Predicted | 0.02-0.03 eV (CMB-S4 testable) |
| Sterile Neutrino DM | ⚠ Predicted | Ms ≈ 0.66 keV, X-ray line at 0.33 keV |
| Baryogenesis | ✓ Derived | epsilon_B = 0.00409 (from SQM washout) |
| The Slab | ✓ Derived | SQM phase transition at T ≈ 0.2866 eV |

---

## Repository Structure

TRC-V24-Tregrwells/
├── README.md                          # This file
├── LICENSE                            # MIT License
├── requirements.txt                   # Python dependencies
│
├── 01_Cosmology_Background.ipynb      # BAO, H0, dark energy evolution
├── 02_Modified_Gravity_S8.ipynb       # Modified gravity, S8 resolution
├── 03_Neutrino_Sector.ipynb           # Neutrino MCMC, θ13 prediction
├── 04_Complete_Test_Suite.ipynb       # All tests in one place
│
└── utils/
    ├── cosmology.py                   # Reusable cosmology functions
    ├── neutrinos.py                   # Reusable neutrino functions
    ├── sqm.py                         # Reusable SQM functions
    └── plots.py                       # Reusable plotting functions

---

## Requirements

- Python 3.8+
- NumPy
- SciPy
- Matplotlib
- emcee (optional, for MCMC)
- corner (optional, for plots)

Install all dependencies with:

pip install -r requirements.txt

---

## How to Run

1. Clone the repository:

git clone https://github.com/YOUR-USERNAME/TRC-V24-Tregrwells.git
cd TRC-V24-Tregrwells

2. Install dependencies:

pip install -r requirements.txt

3. Open a notebook in Google Colab or Jupyter.

4. Run all cells in order.

---

## The Decisive Test: θ13

TRC V24 commits to a sharp, short-term falsification:

- If DUNE/Hyper-K find θ13 = 11-12° (2027-2028), TRC is validated in a way no phenomenological model can match.
- If they find θ13 = 8.5°, TRC is falsified and requires structural refinement.

This binary outcome elevates the framework's scientific status beyond a mere post-hoc fit.

---

## Citation

If you use this work, please cite:

Wells, T. R. (2026). Torsion Rebound Cosmology: A 5D Einstein-Cartan Template for Dark Energy, S8, and a Sharp θ13 Test. Zenodo.  
https://doi.org/10.5281/zenodo.21444517

```bibtex
@misc{Wells2026TRC,
  author = {Wells, Treg Robert},
  title = {Torsion Rebound Cosmology: A 5D Einstein-Cartan Template for Dark Energy, S8, and a Sharp θ13 Test},
  year = {2026},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.21444517},
  url = {https://doi.org/10.5281/zenodo.21444517}
}

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Contact

Treg Robert Wells – Independent Researcher

GitHub: tregrwells

---

## Acknowledgments

The author acknowledges the use of free Google Colab resources and the Python libraries NumPy, SciPy, and Matplotlib. No institutional support or funding was used for this work.

---

TRC V24: A complete, testable unified framework from a single geometric principle.
