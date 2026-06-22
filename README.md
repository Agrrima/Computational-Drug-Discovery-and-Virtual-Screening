# Computational Drug Discovery and Virtual Screening

This repository contains computational drug discovery workflows focused on molecular design, drug-likeness evaluation, and structure-based virtual screening.

## Project: Favipiravir Analog Design and Virtual Screening

A series of Favipiravir analogs were designed and evaluated against the SARS-CoV-2 Main Protease (Mpro, PDB ID: 6LU7) using a cheminformatics and molecular docking pipeline.

### Workflow

* Analog design and molecular structure generation
* Molecular descriptor calculation
* Lipinski Rule of Five evaluation
* Quantitative Estimate of Drug-likeness (QED)
* Synthetic Accessibility (SA) scoring
* 3D conformer generation and MMFF94 energy minimization
* Protein preparation and binding-site identification
* Ligand preparation using Meeko
* Molecular docking using AutoDock Vina
* Lead prioritization based on docking and molecular properties

### Tools and Libraries

* Python
* RDKit
* AutoDock Vina
* Meeko
* Biopython
* Pandas
* NumPy

### Key Findings

The designed analogs demonstrated favorable drug-like properties and successful docking within the active site of SARS-CoV-2 Main Protease. Among the evaluated compounds, the aminomethyl-substituted analog exhibited the strongest predicted binding affinity, while halogenated derivatives showed favorable overall lead-like characteristics.




