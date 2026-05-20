# MTBVeb: A Web-Based Platform for Designing Vaccines against Existing and Emerging Strains of Mycobacterium tuberculosis

## Overview

MTBVeb is a web-based computational platform developed for designing vaccines against existing and emerging strains of *Mycobacterium tuberculosis* (Mtb).

The platform integrates:

- Comparative genomics
- Antigen prediction
- Epitope prediction
- Vaccine candidate identification
- Strain-specific analysis

MTBVeb assists researchers in designing:

- Strain-based vaccines
- Antigen-based vaccines
- Epitope-based vaccines

against drug-sensitive and drug-resistant strains of *Mycobacterium tuberculosis*.

---

# Research Paper Details

## Title

A Web-Based Platform for Designing Vaccines against Existing and Emerging Strains of Mycobacterium tuberculosis

## Authors

- Sandeep Kumar Dhanda
- Pooja Vir
- Deepak Singla
- Sudheer Gupta
- Shailesh Kumar
- Gajendra P. S. Raghava

## Journal

PLoS ONE

## Volume

11

## Issue

4

## Article Number

e0153771

## Published Date

20 April 2016

## Correct DOI

https://doi.org/10.1371/journal.pone.0153771
https://doi.org/10.5281/zenodo.20305682
---

# Background

Tuberculosis remains one of the deadliest infectious diseases worldwide.

Major challenges include:

- Drug-resistant tuberculosis strains
- Limited efficacy of BCG vaccine in adults
- Emerging multidrug-resistant strains
- Lack of effective universal vaccines

Modern technologies such as:

- Next Generation Sequencing (NGS)
- Immunoinformatics
- Epitope prediction
- Comparative genomics

can help accelerate vaccine development against emerging Mtb strains.

MTBVeb was developed to address these challenges using computational approaches.

---

# Objectives

The study aimed to:

- Develop a comprehensive vaccine design platform
- Analyze multiple Mtb strains
- Identify antigenic vaccine candidates
- Predict B-cell and T-cell epitopes
- Support vaccine design against newly sequenced strains
- Integrate genome analysis and epitope prediction tools

---

# Strain Dataset

The study analyzed:

| Strain Category | Number |
|---|---|
| Tuberculoid strains | 23 |
| Vaccine strains | 5 |
| Non-tuberculoid strains | 30 |
| Total strains | 59 |

These included:

- Drug-sensitive strains
- Drug-resistant strains
- Clinical isolates
- Laboratory strains
- BCG vaccine variants

---

# Vaccine Candidate Identification

A total of:

- 178 vaccine candidates
- 166 unique proteins

were identified from literature and previous studies.

## Categories of Vaccine Candidates

### 1. Virulence Associated Proteins

- 125 proteins

### 2. Secretion System Components

- 20 proteins

### 3. Regions of Deletion (RD) Proteins

- 33 proteins

These proteins were analyzed across all strains using sequence similarity search.

---

# Comparative Genomics Analysis

The platform compared vaccine candidate proteins across different Mtb strains.

## Key Findings

- Virulent and secretory proteins differentiate pathogenic and non-pathogenic strains
- RD proteins differentiate vaccine strains from pathogenic strains
- Many vaccine candidates are membrane or extracellular proteins

---

# Epitope Prediction Pipeline

The study generated overlapping 9-mer peptides from vaccine candidate proteins.

## Total Unique Peptides

| Description | Count |
|---|---|
| Unique 9-mer peptides | 103,522 |

---

# Predicted Immune Components

| Immune Feature | Count |
|---|---|
| B-cell epitopes | 8,292 |
| MHC Class I binders | 46,484 |
| CTL epitopes | 34,922 |
| MHC Class II binders | 14,907 |
| Th1 epitopes | 6,242 |
| Th2 epitopes | 9,720 |

---

# Experimentally Validated Epitopes

Experimentally validated epitopes were obtained from:

- Immune Epitope Database (IEDB)

## Mapped Epitopes

| Epitope Type | Unique Peptides |
|---|---|
| B-cell epitopes | 659 |
| T-cell epitopes | 1,806 |
| MHC binders | 1,208 |

Most validated epitopes mapped to vaccine candidate proteins.

---

# Immunoinformatics Tools Integrated

The platform integrated several prediction tools:

| Tool | Purpose |
|---|---|
| LBtope | B-cell epitope prediction |
| Propred | MHC Class II prediction |
| Propred1 | MHC Class I prediction |
| CTLpred | CTL epitope prediction |
| IFNepitope | IFN-gamma epitope prediction |
| IL4pred | IL-4 inducing peptide prediction |

---

# Database Architecture

The database organizes information into:

- Strains
- Antigens
- Epitopes

## Technologies Used

### Backend

- MySQL
- PHP 5.2.9

### Frontend

- HTML
- JavaScript

### Server

- Apache HTTP Server 2.2
- Linux Operating System

---

# Web Server Features

## 1. Strain-Specific Analysis

Allows users to:

- Compare strains
- Analyze newly sequenced genomes
- Identify conserved regions
- Visualize genomes

Integrated genome browsers:

- JBrowse
- CGView
- Argo

---

## 2. Antigen-Based Vaccine Design

Users can:

- Browse vaccine candidates
- Compare vaccine targets
- Perform similarity searches
- Map epitopes on antigens

---

## 3. Epitope-Based Vaccine Design

Users can:

- Predict B-cell epitopes
- Predict T-cell epitopes
- Perform advanced epitope search
- Identify epitopes with desired immune responses

---

# Important Findings

The study demonstrated that:

- Comparative genomics can assist vaccine design
- RD proteins help differentiate vaccine strains
- Immunoinformatics pipelines effectively identify vaccine epitopes
- Large-scale epitope prediction can support subunit vaccine design
- MTBVeb provides more integrated functionality than existing TB vaccine resources

---

# Comparison with Existing Resources

Compared with other TB vaccine databases, MTBVeb provides:

- Strain-specific analysis
- Experimental epitope mapping
- User strain analysis
- Epitope prediction pipelines
- Vaccine strain comparison

---

# Applications

MTBVeb can be used for:

- Tuberculosis vaccine development
- Drug-resistant strain analysis
- Epitope vaccine design
- Comparative genomics
- Immunoinformatics
- Antigen discovery
- Host-pathogen interaction studies

---

# Web Server

http://crdd.osdd.net/raghava/mtbveb/

---

# Citation

Dhanda SK, Vir P, Singla D, Gupta S, Kumar S, Raghava GPS.

A Web-Based Platform for Designing Vaccines against Existing and Emerging Strains of Mycobacterium tuberculosis.

PLoS ONE. 2016;11(4):e0153771.

DOI: https://doi.org/10.1371/journal.pone.0153771

---

# Contact

## Dr. G. P. S. Raghava

Email: raghava@iiitd.ac.in

Address:  
Indraprastha Institute of Information Technology Delhi

---

# License

This project/documentation is intended for academic and research purposes only.
