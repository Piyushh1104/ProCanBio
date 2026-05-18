# PreMieR: Prediction of Mannose Interacting Residues

## Overview

PreMieR is a computational method developed for predicting mannose interacting residues (MIRs) in proteins using local composition-based machine learning approaches.

Mannose-binding proteins (MBPs) are important components of the innate immune system. These proteins recognize mannose molecules present on pathogens and help activate immune defense mechanisms such as complement activation and phagocytosis.

This study introduces Support Vector Machine (SVM)-based prediction models using:

- Binary profile patterns
- Evolutionary information (PSSM)
- Composition profile of patterns (CPP)

Among these, composition-based models achieved the best performance.

---

# Research Paper Details

## Title

Identification of Mannose Interacting Residues Using Local Composition

## Authors

- Sandhya Agarwal
- Nitish Kumar Mishra
- Harinder Singh
- Gajendra P. S. Raghava

## Journal

PLoS ONE

## Year

2011

## Volume and Issue

Volume 6, Issue 9

## Article Number

e24039

## Correct DOI

https://doi.org/10.1371/journal.pone.0024039

---

# Abstract

This study presents machine learning models for predicting mannose interacting residues in proteins.

A dataset of mannose-binding proteins was created from Protein Data Bank (PDB) structures. Different SVM-based approaches were evaluated using:

- Binary profiles
- PSSM evolutionary profiles
- Composition profile patterns

The composition-based approach achieved the best performance with:

- MCC up to 0.74
- Accuracy up to 86.64%

The study also developed a web server and standalone software called **PreMieR**.

---

# Biological Importance

Mannose-binding proteins are involved in:

- Innate immunity
- Pathogen recognition
- Complement activation
- Opsonization
- Phagocytosis

These proteins recognize mannose molecules present on microbial surfaces.

---

# Dataset Information

## Dataset Source

- Protein Data Bank (PDB)
- SuperSite documentation

## Final Dataset

- 120 non-redundant mannose-binding protein chains
- Less than 25% sequence similarity

### Residues

- 1029 mannose interacting residues
- 38136 non-interacting residues

---

# Machine Learning Approaches

## 1. Binary Profile Based SVM

Patterns were encoded into binary vectors.

### Performance

- MCC: 0.19
- Accuracy: 59.60%

---

## 2. PSSM Based SVM

Evolutionary information was incorporated using PSI-BLAST generated PSSM profiles.

### Performance

- MCC: 0.32
- Accuracy: 65.66%

---

## 3. Composition Profile of Patterns (CPP)

Patterns were represented using amino acid composition.

### Best Performance

- MCC: 0.74
- Accuracy: 86.64%

This method significantly outperformed binary and PSSM approaches.

---

# Important Findings

The study found that certain amino acids are preferred in mannose interaction:

- Aspartic acid (D)
- Glutamic acid (E)
- Asparagine (N)
- Glutamine (Q)
- Serine (S)
- Threonine (T)
- Tryptophan (W)
- Tyrosine (Y)

These residues contribute to carbohydrate recognition and binding.

---

# Window Size Analysis

Different pattern lengths were tested:

- 17
- 19
- 21
- 23
- 25

Best performance was obtained using:

- Window size 23
- MCC: 0.74

---

# Evaluation Metrics

The models were evaluated using:

- Sensitivity
- Specificity
- Accuracy
- Matthews Correlation Coefficient (MCC)
- Area Under Curve (AUC)

---

# Web Server

## PreMieR Server

The prediction method was implemented as an online web server.

### Features

- Predict mannose interacting residues
- Adjustable thresholds
- Graphical visualization
- Composition-based prediction

### Server Link

http://www.imtech.res.in/raghava/premier/

---

# Applications

PreMieR can be useful for:

- Protein-carbohydrate interaction analysis
- Immunology research
- Host-pathogen interaction studies
- Functional annotation of proteins
- Drug discovery
- Glycobiology research

---

# Key Technologies

- Support Vector Machine (SVM)
- PSI-BLAST
- Position Specific Scoring Matrix (PSSM)
- Composition Profile of Patterns (CPP)
- Machine Learning
- Bioinformatics

---

# Conclusion

This study demonstrates that local amino acid composition can effectively predict mannose interacting residues in proteins.

The CPP-based approach performed substantially better than binary and evolutionary profile-based methods.

The work provides:

- A benchmark dataset
- A prediction framework
- A publicly accessible web server
- Insight into protein-carbohydrate interactions

---

# Citation

Agarwal S, Mishra NK, Singh H, Raghava GPS (2011)

Identification of Mannose Interacting Residues Using Local Composition.

PLoS ONE 6(9): e24039.

DOI: https://doi.org/10.1371/journal.pone.0024039

---

# Contact

## Dr. G. P. S. Raghava

Email: raghava@iiitd.ac.in

Address:

Indraprastha Institute of Information Technology Delhi

---

# License

This project/documentation is intended for academic and research purposes only.
