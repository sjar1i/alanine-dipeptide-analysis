## Alanine Dipeptide Conformational Analysis

Read Full Report Here:
[COMPUTATIONAL STUDY OF ALANINE DIPEPTIDE CONFORMATIONS.pdf](https://github.com/sjar1i/alanine-dipeptide-analysis/blob/main/COMPUTATIONAL%20STUDY%20OF%20ALANINE%20DIPEPTIDE%20CONFORMATIONS.pdf)

Overview

This project involves the computational study of different conformations of alanine dipeptide, including alpha-helix, beta-sheet, and left-handed alpha conformations. Using the ORCA quantum chemistry software, we optimized the structures and calculated Gibbs free energies to compare their stabilities. MATLAB was used for data analysis and visualization, including the creation of energy landscapes.


Introduction

Alanine dipeptide serves as a model compound for studying peptide conformations due to its simplicity. Understanding the stability and energy landscape of various conformations provides insights into the behavior of larger peptide chains. This project explores the energy differences between alpha-helix, beta-sheet, and various other conformations using computational methods.

Methods

Software

ORCA: Used for geometry optimization and Gibbs free energy calculations.
Avogadro: Utilized for structure visualization and setting initial conformations.

MATLAB: For data analysis, fitting, and visualization of energy landscapes.

Conformational Selection
The study focused on two key conformations:

Alpha Helix: Characterized by torsion angles of φ = -60°, ψ = -40°
Beta Sheet: Characterized by torsion angles of φ = -120°, ψ = 120°

Computational Setup
Structure Optimization: Initial structures were prepared using Avogadro and optimized using ORCA with a suitable level of theory and basis set (def2-SVP).
Frequency Calculations: Performed to verify the nature of the optimized structures and to obtain thermodynamic properties.
Energy Calculations: Gibbs free energies were computed, and single-point energies were calculated for additional analysis.
Results
Gibbs Free Energy Calculations
The calculated Gibbs free energies (in Hartrees) for each conformation are:

Alpha Helix: -492.33052547 Eh
Beta Sheet: -492.33186378 Eh
phi = 54, psi = -74: -492.33261610 Eh
phi = -73, psi = 72: -492.33165235 Eh
phi = -20, psi = -55: -492.33049380 Eh
phi = 168, psi = -79: -492.32740611 Eh


Energy Landscape Visualization
A 3D energy landscape was created using MATLAB to illustrate how the Gibbs free energy changes across different torsion angles (φ, ψ). Specific energy points for each conformation were marked on the graph to highlight their relative stabilities.


Conclusion
The results indicate that the phi = 54, psi = -74 conformer was the most stable and the phi = 168, psi = -79 was the least stable, while both alpha helix and beta sheet conformers were both relatively stable. The energy landscape provides a visual representation of the stability trends across different torsion angles, offering insights into the behavior of alanine dipeptide.

Files
Orca input and output files
Avogadro cml files
MATLAB code for graphing
Figures and plots - Ramachandran Plot: https://www.researchgate.net/figure/Ramachandran-map-of-the-alanine-dipeptide-in-its-ph-ps-space-with-the-locations-of_fig1_250612549
