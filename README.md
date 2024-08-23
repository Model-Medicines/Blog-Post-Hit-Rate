# Tanimoto Similarity Analysis | AI Hit Rate Blog

This repository contains code and data for calculating Tanimoto similarity to training data, ChEMBL data, and Pairwise Diversity Scores. 
The chemical compounds were extracted from select publications, and calculations were performed using their SMILES strings and ECFP4 fingerprints.

## Repository Structure

- **data/**: Contains the raw and processed datasets.
  - **Paper 1/**: Data related to Paper 1 (DOI: 10.1126/sciadv.abg3338).
  - **Paper 2/**: Data related to Paper 2 (DOI: 10.1021/acs.jcim.2c00068).
  - **Paper 4/**: Data related to Paper 4 (DOI: 10.1021/acsmedchemlett.2c00515).
  - **Paper 5/**: Data related to Paper 5 (DOI: 10.1038/s42004-022-00733-0).
  - **Paper 6/**: Data related to Paper 6 (DOI: 10.48550/arXiv.2402.08210).
  - **Paper 7/**: Data related to Paper 7 (DOI: 10.1038/s42256-024-00809-7).
  - **Paper 9/**: Data related to Paper 9 (DOI: 10.1021/acs.jmedchem.2c00931).

- **Tanimoto_Similarity_Analysis.ipynb**: Jupyter Notebook containing the code for SMILES cleaning, fingerprint generation, and Tanimoto calculations.


