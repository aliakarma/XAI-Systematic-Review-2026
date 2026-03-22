# Data Files

All supplementary data files are organised into three subfolders.
---

## `search/`
Files related to the database search strategy.

| Filename | Description |
|----------|-------------|
| `Search_Strings.xlsx` | Boolean search queries used across all 6 databases (Scopus, Web of Science, IEEE Xplore, ACM Digital Library, ScienceDirect, SpringerLink). Includes field codes, date range, and query variations per database. |

---

## `screening/`
Files related to study selection and PRISMA screening.

| Filename | Description |
|----------|-------------|
| `Screening_Database.xlsx` | Full 228-record title/abstract and full-text screening log with reviewer decisions |
| `PRISMA_Summary.xlsx` | PRISMA 2020 summary: records identified, duplicates removed, screened, assessed, and included |
| `Cohen_Kappa_Calculator.xlsx` | Inter-rater agreement calculation (κ = 0.823) for full-text screening stage |

---

## `extraction/`
Files related to data extraction from included studies.

| Filename | Description |
|----------|-------------|
| `XAI_188_References_Final_18col.csv` | Final dataset of 188 included studies with 18 columns: metadata, XAI technique, domain, evaluation metrics, quality score, limitations, and DOI (with hyperlinks) |
| `XAI_188_PRISMA_Screening.csv` | 188 included studies with PRISMA screening decisions and reviewer fields |
| `XAI_228_PRISMA_Full_Screening.csv` | Complete screening log: 188 included + 40 excluded studies with exclusion reasons and inter-reviewer agreement |

---

## Column Schema — XAI_188_References_Final_18col.csv

| # | Column | Description |
|---|--------|-------------|
| 1 | Record ID | Sequential identifier (1–188) |
| 2 | Title | Full paper title |
| 3 | Authors | Author list |
| 4 | Year | Publication year |
| 5 | Journal / Conference | Venue name |
| 6 | Application Domain | Healthcare / Finance / Cybersecurity / Robotics / Agentic AI / All Domains |
| 7 | Model Category | ML / DL / RL / LLM / Hybrid |
| 8 | Specific Model(s) | e.g., ResNet, BERT, XGBoost |
| 9 | XAI Technique(s) Applied | e.g., SHAP, LIME, Grad-CAM, LRP |
| 10 | XAI Category | Model-Agnostic / Post-Hoc / Model-Specific |
| 11 | Dataset Used | Primary dataset(s) reported |
| 12 | Evaluation Metric(s) | e.g., AOPC, AUC, faithfulness score |
| 13 | Evaluation Framework Dimension Met | F / P / S / C / Cost / Domain |
| 14 | Key Contribution | One-sentence summary |
| 15 | Quality Score | High / Medium / Low |
| 16 | Limitations Noted | Key limitations from the paper |
| 17 | Notes | Additional context |
| 18 | DOI | Verified DOI with clickable hyperlink formula |

---

## Column Schema — XAI_228_PRISMA_Full_Screening.csv

| # | Column | Description |
|---|--------|-------------|
| 1 | Record ID | Sequential (1–228) |
| 2 | Title | Paper title |
| 3 | Authors | Authors |
| 4 | Year | Year |
| 5 | Journal / Conference | Venue |
| 6 | Source Database | Database where record was retrieved |
| 7 | T/A Decision | Include / Exclude (title & abstract stage) |
| 8 | T/A Exclusion Reason | Reason if excluded at T/A stage |
| 9 | Full-Text Retrieved? | Yes / No |
| 10 | FT Decision | Include / Exclude (full-text stage) |
| 11 | FT Exclusion Reason | Reason if excluded at full-text stage |
| 12 | Final Status | Included / Excluded |
| 13 | Reviewer 1 | Reviewer 1 decision |
| 14 | Reviewer 2 | Reviewer 2 decision |
| 15 | Agreement? | Yes / No |
| 16 | Notes | Domain label and additional notes |

---

## License

All data files are released under **Creative Commons CC0 1.0 (Public Domain)**.
You may use, share, and adapt freely with no attribution required,
though citation of the source paper is appreciated.
