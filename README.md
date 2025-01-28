# aiqm2
This repository contains analysis scripts and results for:

AIQM2: Better Reaction Simulations with the 2nd Generation of General-Purpose AI-enhanced Quantum Mechanical Methods

Preprint on ChemRxiv: [https://doi.org/10.26434/chemrxiv-2024-c8s16](https://doi.org/10.26434/chemrxiv-2024-j8pxp)

## gmtkn55
This folder contains the results for the benchmark on GMTKN55 arranged by level of theories. There are four files under each subfolder:

- `MAE_summary`: The MAE for each subset in GMTKN55.
- `molecule_summary`: The total energy of each molecule and the uncertainty (for AIQM series methods) in kcal/mol.
- `reaction_summary`: The relative energy in kcal/mol for each reaction in GMTKN55.
- `WTMAD2_summary`: The WTMAD-2 in kcal/mol for each category and the whole GMTKN55.

## BHPERI
This folder contains two subfolders. `gmtkn55` stores geometry optimization results of AIQM2 on each transition state in BHPERI from GMTKN55. 

We reevaluated AIQM2 on 3 reactions from BHPERI whose geometries are optimized at CCSD(T)/cc-pVTZ in a recent study [_Phys. Chem. Chem. Phys._ **2022**, 24, 18028–18042]. The optimized geometries and single point energies are included in folder `revised_PCCP`

- `DA`: The Diels-Alder reaction starting from trans-butadiene and ethylene
- `ER`: The electrocyclic ring-opening reaction starting from cyclobutene
- `SR`: The sigmatropic rearrangement originating from the E-isomer of 1,3-pentadiene

## ambimodal
This folder contains optimized geometries and single point energies for reactants, 2 products, and transition states at each level of theory for ambimodal reaction between 
tropone and dimethylfulvene studied in previous work. [_J. Am. Chem. Soc._ **2017**, 139, 8251–8258]

## To be updated

- Jupiter notebooks for calculation and analysis of ambimodal reactions
