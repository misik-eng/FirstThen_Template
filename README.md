# FirstThen Data Analysis

Internal data analysis repository developed for the **FirstThen** project.
This repository follows the MIT Emerging Talent CDSP Starter structure and
contains code, notebooks, and documentation to support data-driven insights,
clinical feasibility evaluation, and organizational decision-making.

> ⚠️ Confidential: All materials in this repository are proprietary and
> restricted to internal use by authorized FirstThen team members only.

---

## Project Overview

This project focuses on cleaning, integrating, and analyzing clinical and
feasibility datasets. It aims to generate actionable insights, visualize key
patterns, and support internal research objectives. The repository structure
aligns with the analytical workflow used across the MIT ET CDSP framework.

---

## Repository Structure

0_domain_study/           # Background research and contextual documentation  
1_datasets/               # Source data (excluded via .gitignore)  
2_data_preparation/       # Data cleaning and preprocessing scripts  
3_data_exploration/       # Exploratory Data Analysis notebooks  
4_data_analysis/          # Statistical modeling and feature evaluation  
5_communication_strategy/ # Visualization and reporting preparation  
6_final_presentation/     # Deliverables and presentation materials  
LICENSE                   # Proprietary license terms  
.gitignore                # Git tracking exclusions  
requirements.txt          # Python dependencies  
README.md                 # Project documentation  

---

## Environment Setup

```bash
git clone https://github.com/awsFirstThen/FirstThen-data-analysis.git
cd FirstThen-data-analysis

python3 -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

---

## Technical Goals

- Standardize and document data ingestion and preparation steps  
- Perform exploratory and inferential analyses on feasibility datasets  
- Identify trends and outliers using statistical and visualization methods  
- Deliver interpretable insights aligned with project objectives  

---

## Data Governance

- All datasets under `/1_datasets/` are excluded from version control  
- Sensitive or personally identifiable data must **never** be uploaded  
- Derived or aggregated datasets must remain compliant with internal
  confidentiality policies  
- Only de-identified, representative samples may be shared in notebooks  

---

## License

Proprietary License © 2025 FirstThen, Inc.  
All rights reserved. Unauthorized use or distribution is prohibited.

---

## Maintainers

- **Sahar Omer** – Data Science Intern  
- **Ali Isik** – Data Science Intern  
- **Amanda Schnetzer** – Project Lead, FirstThen  
