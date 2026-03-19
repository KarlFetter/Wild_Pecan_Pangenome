# Wild Pecan Pangenome

![Wild Pecan Pangenome](assets/landing.png)

## Overview

This repository contains code and key results for the construction and analysis of a wild pecan (*Carya illinoinensis*) pangenome. The project spans pangenome assembly, variant detection, and trait mapping across diverse wild pecan accessions.

> **Note:** This is a public repository. Scripts, workflows, and summary results are shared here. Raw sequence data and sensitive phenotype files are not included. See [Data Availability](#data-availability) for access information.

---

## Project Structure

```
Wild_Pecan_Pangenome/
├── 01_Pangenome/            # Pangenome construction methods and results
├── 02_Variant_Detection/    # Variant calling against the pangenome graph
├── 03_Trait_Mapping/        # GWAS and trait-marker association analyses
├── assets/                  # Figures and images
└── results/                 # Key summary results and tables
```

## Data Availability

**BioProject:** *TBD*

| Data Type | Accession | Description |
|-----------|-----------|-------------|
| HiFi Reads | *TBD* | PacBio HiFi sequencing |
| Pangenome | *TBD* | Graph-based pangenome |
| Variants | *TBD* | Structural and small variants |

---

## Methods

- **[01 — Pangenome Construction](01_Pangenome/README.md)** — Assembly, graph construction, and pangenome evaluation
- **[02 — Variant Detection](02_Variant_Detection/README.md)** — Variant calling, filtering, and annotation
- **[03 — Trait Mapping](03_Trait_Mapping/README.md)** — GWAS and genotype–phenotype association

---

## Compute Environment

- **HPC:** USDA ARS SCINet Ceres cluster
- **Scheduler:** SLURM

---

## Contact & Collaborators

Karl Fetter — karl.fetter@usda.gov \
Research Geneticist \
Tree Genomics Lab \
USDA ARS Southeastern Fruit & Tree Nut Research Station \
Byron, GA

Cristina Pisani - cristina.pisani@usda.gov \
Research Horticulturist \
USDA ARS Southeastern Fruit & Tree Nut Research Station \
Byron, GA

Jeeking Lau- jeekin.lau@usda.gov \
Research Geneticist \
USDA ARS Southeastern Fruit & Tree Nut Research Station \
Byron, GA

Roth Conrad \
USDA ARS Postdoctoral Fellow \
Genome Biology Research Unit \
Athens, GA

Gaurab Bhattarai \
Assistant Professor \
Oregon State University \
Corvalis, OR




