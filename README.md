# Analysis of the 1MBO Protein with Homology Modelling and Molecular Docking

This repository contains the materials for a structural bioinformatics project focused on the analysis of the myoglobin protein (1MBO) and its interaction with the HEME ligand.

## Project Overview

The goal of this project was to explore the structural and functional properties of myoglobin through a multi-step computational workflow. The work included protein preparation, interface analysis, solvent accessible surface area (SASA) calculations, homology modelling, molecular docking, and hotspot identification.

## Methods

- Prepared the 1MBO crystal structure in PyMOL by removing solvent, adding hydrogens, and separating the protein chain, HEME ligand, and full complex.
- Identified interface residues involved in protein–ligand interaction and analyzed the local binding environment.
- Calculated SASA-related metrics using PDBePISA and processed the outputs with a custom Python script to obtain ΔSASA and relative SASA values.
- Generated and compared homology models using SWISS-MODEL, AlphaFold2, and ESM to evaluate structural prediction quality against the crystal structure.
- Performed molecular docking with HADDOCK 2.4 using blind docking, random patches, and active/passive residue-based strategies to investigate binding modes.
- Used Hotspot Wizard to identify residues associated with structural stability and ligand interaction.

## Repository Contents

- `report/` – full written report of the project.
- `presentation/` – presentation slides summarizing the workflow and results.
- `data/` – FASTA sequence of the 1MBO protein.
- `figures/` – structural images and visual outputs from the analysis.

## Tools and Resources

- PyMOL
- PDBePISA
- SWISS-MODEL
- AlphaFold2
- ESM
- HADDOCK 2.4
- Hotspot Wizard
- Python

## Key Outcomes

This project provided a practical overview of structural bioinformatics methods used to study protein–ligand systems. It combined visualization, structural comparison, docking, and interface analysis to better understand the interaction between myoglobin and HEME, while also highlighting the strengths of modern homology modelling approaches.
