# Trustworthy AI Through Explainability: A Systematic Review of XAI Techniques and Their Role in Safety-Critical Domains

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![PRISMA 2020](https://img.shields.io/badge/PRISMA-2020%20Compliant-blue)](https://www.prisma-statement.org/)
[![Studies Included](https://img.shields.io/badge/Studies%20Included-188-green)]()
[![Domains](https://img.shields.io/badge/Domains-5-orange)]()

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19570781.svg)](https://doi.org/10.5281/zenodo.19570781)

[![PRISMA 188 Screening](https://img.shields.io/badge/Download-PRISMA_188_Screening-blue?style=for-the-badge&logo=github)](https://github.com/aliakarma/XAI-Systematic-Review-2026/blob/master/data/extraction/XAI_188_PRISMA_Screening.xlsx)

[![References Final](https://img.shields.io/badge/Download-References_Final-green?style=for-the-badge&logo=github)](https://github.com/aliakarma/XAI-Systematic-Review-2026/blob/master/data/extraction/XAI_188_References_Final_18col.xlsx)

[![PRISMA 228 Full](https://img.shields.io/badge/Download-PRISMA_228_Full-orange?style=for-the-badge&logo=github)](https://github.com/aliakarma/XAI-Systematic-Review-2026/blob/master/data/extraction/XAI_228_PRISMA_Full_Screening.xlsx)

---

## Overview

This repository contains all supplementary data, figures, and bibliography for the above systematic review, published in 2026.

This PRISMA 2020-compliant review synthesises **188 peer-reviewed studies** on Explainable Artificial Intelligence (XAI) across five safety-critical domains: **healthcare, finance, cybersecurity, robotics, and agentic AI**.

---

## Repository Structure

```
XAI-Systematic-Review-2026/
│
├── figures/
│   ├── background/          # ML/DL/LLM architecture figures (Section III)
│   ├── methodology/         # PRISMA flow and review workflow (Section II)
│   ├── xai_techniques/      # Post-hoc methods and XAI timeline (Section IV)
│   ├── domain_taxonomies/   # Per-domain XAI taxonomy figures (Section V)
│   └── synthesis/           # Cross-domain trends and geographic map (Section VI)
│
├── data/
│   ├── search/              # Boolean search strings (6 databases)
│   ├── screening/           # PRISMA screening database (228 records)
│   └── extraction/          # Data extraction form and 188-reference dataset
│
└── bibliography/            # Complete BibTeX file (188 references, DOIs, URLs)
```

---

## Key Findings

- **188 studies** included from 6 databases (Scopus, WoS, IEEE Xplore, ACM DL, ScienceDirect, SpringerLink)
- **SHAP and LIME** are the most widely deployed XAI techniques across all five domains
- **Grad-CAM and LRP** dominate medical imaging and robotic perception tasks
- **Agentic AI** requires XAI beyond feature attribution: intention modelling, action-sequence reasoning, and multi-agent governance
- **North America** (85 papers) and **Europe** (50 papers) dominate global output; Africa and South America remain critically underrepresented

---

## Domain Coverage

| Domain | Papers |
|--------|--------|
| Healthcare | 36 |
| Robotics | 33 |
| General / Multi-domain | 76 |
| Agentic AI | 22 |
| Finance | 11 |
| Cybersecurity | 10 |

---

## Data Files Summary

| File | Description |
|------|-------------|
| `data/search/Search_Strings.xlsx` | Boolean queries used across all 6 databases |
| `data/screening/Screening_Database.xlsx` | Full 228-record screening log |
| `data/screening/PRISMA_Summary.xlsx` | PRISMA 2020 summary counts |
| `data/screening/Cohen_Kappa_Calculator.xlsx` | Inter-rater agreement (κ = 0.823) |
| `data/extraction/Data_Extraction_Form.xlsx` | Standardised extraction template |
| `data/extraction/XAI_188_References_Final_18col.csv` | Final 188 studies with 18 columns including DOIs |
| `data/extraction/XAI_188_PRISMA_Screening.csv` | 188 included studies with screening decisions |
| `data/extraction/XAI_228_PRISMA_Full_Screening.csv` | All 228 screened records (188 included + 40 excluded) |
| `bibliography/references_final.bib` | Complete BibTeX file with DOIs and URLs |

---

## Data Availability

All supplementary data is also permanently archived on Zenodo:
**DOI: https://doi.org/10.5281/zenodo.19570781**

---

## License

- **Figures:** Creative Commons Attribution 4.0 (CC BY 4.0)
- **Data files:** Creative Commons CC0 1.0 (Public Domain)

See `LICENSE` for full terms.
