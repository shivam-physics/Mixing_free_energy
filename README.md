# Beyond Regular Solution Theory: Quasi-Chemical Approximation of Lipid Mixing Thermodynamics
## Repository Contents

This repository contains the molecular simulation data, topology files, and analysis outputs used in this study.

The data are organized into directories corresponding to different lipid mixtures and their compositions.

### Directory Structure

- **`1-DOPE-DPPE/` - `11-DTPC-DFPC/`**: Data for the binary lipid mixtures investigated in this study. Each directory contains subdirectories corresponding to different mole fractions (0–100%) of the second lipid component.

- **`chol/`**: Data for ternary lipid mixtures containing DIPC, DPPC, and cholesterol at different compositions.

- **`DFPC_DTPC/`**: Molecular simulation input and structural files for DTPC–DFPC mixtures at different DFPC mole fractions (10–90%).

- **`toppar/`**: Martini force-field parameter and lipid topology files required for the molecular simulations.

- **`production.mdp`**: GROMACS molecular dynamics production-run parameter file.

### File Descriptions

The following files are provided within the corresponding composition directories:

| File | Description |
|---|---|
| `*_qca.dat` | QCA analysis data for the corresponding lipid composition. |
| `*_interaction_matrix.dat` | Effective pairwise interaction matrix obtained from the analysis. |
| `*_topol.top` | GROMACS topology file for the corresponding lipid mixture. |
| `clust.dat` | Cluster analysis data for the corresponding composition. |
| `qca_summary.csv` | Summary of QCA-derived thermodynamic and structural quantities. |
| `npt.gro` | Final molecular configuration obtained from the NPT simulation. |
| `npt.tpr` | GROMACS run-input file for the NPT simulation. |

### Citation
If you use these data, please cite:
Shivam Gupta and Taraknath Mandal, Beyond Regular Solution Theory: Quasi-Chemical Approximation of Lipid Mixing Thermodynamics, XXXX.
