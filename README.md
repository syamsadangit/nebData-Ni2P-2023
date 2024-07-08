# Nudged Elastic Band (NEB) Calculations for HER on Ni<sub>3</sub>P<sub>2</sub> Surface

This repository contains data of Nudged elastic band calculations focused on understanding the Volmer-Volmer-Tafel and Volmer-Heyrovsky pathways for the Hydrogen Evolution Reaction (HER) on Ni<sub>3</sub>P<sub>2</sub> and Ni<sub>3</sub>P<sub>2</sub> + 4P surfaces.

### README.md:

- **README.md**:
  - This file, providing an overview of the directory structure and contents for understanding the NEB calculations.

## Usage and Interpretation:

- These directories and files represent atomic structures and energy profile of various pathways of NEB calculations for HER on Ni<sub>3</sub>P<sub>2</sub> surfaces.
- POSCAR/CONTCAR has the atomic positions. INCAR files contain input paramenters for VASP software to reproduce the results. nebef.dat has the NEB results. .agr file has the plotted data (use xmgrace to view). 

## Directory Structure and Contents

### Directories:

- **3to4to5Taf-3to3**:
  - NEB calculations for the Volmer-Volmer-Tafel pathway from 3H adsorption coverage to 4H coverage to 5H coverage, and back to 3H by Tafel.

- **4to5Hey4**:
  - NEB calculations for the Volmer-Heyrovsky pathway from 4H adsorption coverage to 5H coverage and back to 4H by Heyrovsky.

- **4to5Hey4-2**:
  - Another NEB calculations for another variant of the Volmer-Heyrovsky pathway from 4H adsorption coverage to 5H coverage and back to 4H by Heyrovsky.

- **4to5to6Taf-1to4**:
  - NEB calculations for the Volmer-Volmer-Tafel pathway from 4H adsorption coverage to 5H coverage to 6H coverage and back to 4H by Tafel.

- **4to5to6Taf-2to4**:
  - Another NEB calculations for the Volmer-Volmer-Tafel pathway from 4H adsorption coverage to 5H coverage to 6H coverage and back to 4H by Tafel.

- **6to7Hey6-1**:
  - NEB calculations for the Volmer-Heyrovsky pathway from 6H adsorption coverage to 7H coverage and back to 6H by Heyrovsky.

- **6to7Hey6-2**:
  - Another NEB calculations for the Volmer-Heyrovsky pathway from 6H adsorption coverage to 7H coverage and back to 6H by Heyrovsky.

- **6to7to8Taf-3to6**:
  - NEB calculations for the Volmer-Volmer-Tafel pathway from 6H adsorption coverage to 7H coverage to 8H coverage and back to 6H by Tafel.

- **7-II-adatomto6Hey-1**:
  - NEB calculations for the Volmer-Heyrovsky pathway from coverage 7H (II) to 6H adsorption coverage.

### Files:

- **H2**:
  - Hydrogen in solvent.

- **adatom_Ni3P2_Solvent**:
  - Additional data related to the adatom configuration on Ni<sub>3</sub>P<sub>2</sub> surface with solvent.

- **Ni3P2_Solvent**:
  - Additional data related to Ni<sub>3</sub>P<sub>2</sub> surface with solvent configuration.

- **Tafel-final-no-H2**:
  - Data on the final state of Tafel pathway excluding hydrogen (H<sub>2</sub> appx).


