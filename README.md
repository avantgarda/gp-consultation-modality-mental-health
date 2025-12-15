# Association between primary care consultation modality and acute mental health service use

Analytic code for a retrospective cohort study examining associations between
primary care consultation modality and acute mental health service use in South
London, using linked secondary and primary care data (CRIS–LDN).

## Study overview

This repository contains the analytic scripts used in the study:

**Association between primary care consultation modality and acute mental health
service use: a retrospective cohort study**

The study investigates whether the proportion of remote consultations in primary
care (telephone, text, email, or video) is associated with subsequent acute mental
health service use, including emergency contacts with mental health liaison teams,
psychiatric hospital admissions, inpatient bed-days, and compulsory admissions
under the Mental Health Act.

## Repository contents

- `notebooks/`
  - `01_data_cleaning.ipynb`  
    Data cleaning, cohort construction, and derivation of analytic variables.
  - `02_statistical_analysis.ipynb`  
    Statistical analyses using Generalised Estimating Equations with negative
    binomial models, including multiple imputation by chained equations.

- `data/`
  - `README.md`  
    Information on data availability and governance restrictions.

- `requirements.txt`  
  Python package dependencies required to run the analyses.

## Data availability

The data used in this study are derived from pseudonymised electronic health
records from the Clinical Record Interactive Search (CRIS) system at South London
and Maudsley NHS Foundation Trust, linked to primary care consultation data from
Lambeth DataNet (LDN).

Due to ethical approvals and NHS information governance requirements, the raw
patient-level data are not publicly available and are not included in this
repository. Access to the data is restricted to approved researchers and subject
to the relevant governance processes.

## Reproducibility

This repository provides the analytic code required to reproduce the analytical
approach described in the manuscript, subject to appropriate data access. The
analyses were conducted using Python 3.11 and the packages listed in
`requirements.txt`.

## Licence

This code is released under the MIT License. See the `LICENSE` file for details.
