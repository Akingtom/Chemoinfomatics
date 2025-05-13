# Introduction to Cheminformatics - Tutorial Implementation

## Overview
This repository contains my implementation of the cheminformatics tutorial organized by Ariane Nunes-Alves at Technical University Berlin. The tutorial is adapted from Menke et al. (https://doi.org/10.1002/ardp.202200628). 

## About This Repository
This repository documents my learning journey through the tutorial notebook created by Ariane Nunes-Alves at Technical University Berlin. By sharing my implementation, I hope it might be helpful to others learning cheminformatics. I've added my own comments and notes based on my understanding of the concepts.

## Original Tutorial Credits
- **Instructor**: Ariane Nunes-Alves
- **Institution**: Technical University Berlin
- **Based on**: Materials from Menke et al. (https://doi.org/10.1002/ardp.202200628)

Please refer to the original sources for the complete educational context.

## What I Learned
Through this tutorial implementation, I learned about:
- Molecular representations using SMILES format
- Processing molecules with RDKit
- Accessing and manipulating molecular properties
- Calculating molecular descriptors
- Drug-likeness assessment using Lipinski's Rule of Five
- Molecular fingerprints and similarity search

## Notebook Contents
- **Cheminformatics_v4.2.ipynb**: My implementation of the tutorial covering:
  - Section A: Molecular representations
  - Section B: Accessing basic molecular properties
  - Section C: Calculating molecular descriptors
  - Section D: Fingerprints & Similarity Search

## Setup and Dependencies
To run this notebook, you'll need:
- Python 3.6+
- RDKit (`pip install rdkit`)
- NumPy (`pip install numpy`)
- Optional: Mordred (for additional molecular descriptors)
- Optional: Pandas (for data structuring)

You can run the notebook either:
- Locally with Jupyter
- On Google Colab (the notebook includes code to install dependencies automatically)

## Key Highlights
The tutorial covers a practical case study analyzing Sorafenib (a kinase inhibitor used for treating kidney cancer) and includes:
- Visualization of molecular structures
- Calculation of physicochemical properties
- Drug-likeness evaluation using Lipinski's Rule of Five
- Molecular similarity comparison using fingerprints

## References
- Nunes-Alves, A., Technical University Berlin (tutorial organizer)
- Menke et al. (2022): https://doi.org/10.1002/ardp.202200628
- RDKit Documentation: https://www.rdkit.org/docs/
- Daylight Theory Manual (SMILES): https://www.daylight.com/dayhtml/doc/theory/theory.smiles.html
- Lipinski's Rule of Five: Lipinski et al. (1997) https://doi.org/10.1016/S0169-409X(96)00423-1

## Disclaimer
This repository is for educational purposes only. I am not the author of the original tutorial content but a student implementing it to learn. All credit for the educational materials goes to Ariane Nunes-Alves at Technical University Berlin and the referenced authors.

## License
This implementation is shared under [your preferred license], while respecting the original tutorial's copyright.
