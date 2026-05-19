# ProCanBio: A Database of Manually Curated Biomarkers for Prostate Cancer

## Overview

ProCanBio is a manually curated database developed for maintaining comprehensive information about biomarkers associated with Prostate Cancer.

The database integrates biomarker information collected from published literature and provides detailed annotations regarding:

- Diagnostic biomarkers
- Prognostic biomarkers
- Predictive biomarkers
- Genomics data
- Proteomics data
- Metabolomics data
- Epigenomics data

ProCanBio was developed to provide a centralized resource for prostate cancer biomarker research and analysis.

---

# Research Paper Details

## Title

ProCanBio: a database of manually curated biomarkers for Prostate Cancer

## Authors

- Dikscha Sapra
- Harpreet Kaur
- Anjali Dhall
- Gajendra P. S. Raghava


## Published Date
 10 december 2021

## DOI
https://doi.org/10.1089/cmb.2021.0348



---

# Background

Prostate Cancer is one of the most common malignancies in men worldwide and is associated with high mortality.

Traditional biomarkers such as:

- PSA (Prostate Specific Antigen)

lack sufficient specificity because elevated PSA levels are also associated with:

- Benign Prostatic Hyperplasia (BPH)
- Prostatitis
- Prostatic Intraepithelial Neoplasia (PIN)

Therefore, there is a need for more reliable biomarkers for:

- Diagnosis
- Prognosis
- Therapeutic response prediction

Although numerous studies have identified prostate cancer biomarkers, the information was scattered across multiple publications in unstructured formats.

ProCanBio was developed to consolidate this information into a single user-friendly resource.

---

# Objectives

The study aimed to:

- Develop a manually curated prostate cancer biomarker database
- Consolidate biomarker information from published literature
- Provide detailed annotations for each biomarker
- Develop advanced search and browsing tools
- Facilitate biomarker research and validation

---

# Data Collection

Two PubMed keyword searches were performed:

1. `"prostate cancer" AND biomarkers`
2. `"prostate cancer" AND signatures`

## Literature Statistics

| Description | Count |
|---|---|
| Total publications retrieved | 4045 |
| Duplicate publications removed | 112 |
| Publications manually curated | 412 |

The curated information was extracted manually from published articles.

---

# Database Statistics

## Total Entries

| Category | Count |
|---|---|
| Total biomarker entries | 2053 |
| Unique biomarkers | 1497 |

---

# Biomolecule Distribution

| Biomolecule Type | Count |
|---|---|
| Protein biomarkers | 766 |
| RNA biomarkers | 488 |
| miRNA biomarkers | 261 |
| Metabolite biomarkers | 122 |
| DNA biomarkers | 19 |

---

# Biomarker Basis

| Biomarker Basis | Count |
|---|---|
| Expression-based | 1286 |
| Concentration-based | 378 |
| Methylation-based | 218 |
| Mutation-based | 157 |

---

# Source of Biomarkers

| Source | Count |
|---|---|
| Tissue | 1069 |
| Serum | 354 |
| Blood | 245 |
| Urine | 170 |
| Plasma | 137 |
| Cell lines | 51 |

---

# Types of Biomarkers

The database contains:

- Diagnostic biomarkers
- Prognostic biomarkers
- Predictive biomarkers

## Major Uses

### Diagnostic Biomarkers

Used for distinguishing:

- Prostate cancer
- Healthy controls
- BPH
- PIN
- Prostatitis

### Prognostic Biomarkers

Used for:

- Gleason score prediction
- Metastasis prediction
- Survival analysis
- Biochemical recurrence prediction

### Predictive Biomarkers

Used for:

- Therapy response prediction
- Drug response analysis

---

# Top Biomarkers in ProCanBio

| Biomarker | Biomolecule | Number of Studies |
|---|---|---|
| PCA3 | mRNA/Protein | 17 |
| Ki-67 | Protein | 9 |
| Prostate Health Index (phi) | mRNA/Protein | 9 |
| miR-141 | miRNA | 8 |
| PSA | mRNA/Protein | 5 |
| PTEN | mRNA/Protein/DNA | 4 |

---

# Information Stored for Each Biomarker

Each biomarker entry includes:

- PubMed ID
- Biomarker name
- Technical name
- Biomolecule type
- Biomarker basis
- Regulation status
- Source of biomarker
- Patient cohort
- Sensitivity
- Specificity
- ROC-AUC
- Accuracy
- p-value
- Hazard Ratio (HR)
- Odds Ratio (OR)
- Experimental methods
- Clinical trial information
- Degree of validity

---

# Web Server Architecture

The database was developed using:

## Backend

- MySQL v8

## Frontend

- PHP v7
- HTML5
- JavaScript
- CSS3

## Server

- Apache HTTP Server
- Linux platform

---

# Query and Search Tools

## Keyword Search

Allows searching using:

- Biomarker name
- Biomolecule
- PMID
- Subjects
- Regulation conditions

---

## Complex Search

Supports multiple query conditions including:

- Biomolecule
- Biomarker type
- Source
- Publication year
- Subjects

Logical operators supported:

- AND
- OR
- NOT

---

## Browse Tools

Users can browse biomarkers based on:

- Biomolecule
- Biomarker type
- Source
- Biomarker basis

---

# Web Server Features

ProCanBio provides:

- Advanced keyword search
- Complex search queries
- Browsing tools
- Biomarker cards
- Downloadable results
- Clinical trial links
- GeneCards integration
- PubMed integration

## Download Formats

- CSV
- XLS
- PDF

---

# Case Studies

## PSMA Biomarker Query

The database identified:

- 15 unique PSMA entries
- Derived from 6 research publications

PSMA was mainly used for:

- Diagnostic applications

---

## Prognostic Protein Biomarkers after 2015

Complex search identified:

- 23 unique prognostic protein biomarkers

Important biomarkers included:

- WISP1
- Ki-67
- GLUT1
- AZGP1

---

# Applications

ProCanBio can be used for:

- Biomarker discovery
- Cancer genomics research
- Proteomics research
- Clinical biomarker validation
- Drug target analysis
- Precision oncology
- Prostate cancer diagnostics
- Prognostic biomarker analysis

---

# Technologies Used

- MySQL
- PHP
- Apache Server
- JavaScript
- HTML5
- CSS3
- Manual Literature Curation
- Bioinformatics Database Systems

---

# Important Findings

The study demonstrated that:

- Prostate cancer biomarker information is highly scattered
- Manual curation significantly improves accessibility
- Integrated biomarker databases facilitate cancer research
- Multi-omics biomarker resources are highly valuable

---

# Conclusion

ProCanBio provides a comprehensive manually curated resource for prostate cancer biomarkers.

The database integrates:

- Genomics
- Transcriptomics
- Proteomics
- Metabolomics
- Clinical biomarker information

with advanced search and browsing capabilities, making it a valuable resource for prostate cancer research and biomarker discovery.

---

# Web Server

https://webs.iiitd.edu.in/raghava/procanbio/

---

# Citation

Sapra D, Kaur H, Dhall A, Raghava GPS.

ProCanBio: a database of manually curated biomarkers for Prostate Cancer.


---

# Contact

## Dr. G. P. S. Raghava

Email: raghava@iiitd.ac.in

Address:  
Indraprastha Institute of Information Technology Delhi

---

# License

This project/documentation is intended for academic and research purposes only.
