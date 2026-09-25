# HIV Incidence Among People Who Inject Drugs in Pakistan

## Overview

This repository contains the R code and supporting documentation used for the analysis of HIV incidence among people who inject drugs (PWID) in Pakistan.

The analyses were conducted using programmatic data collected by **Nai Zindagi Trust (NZT)**, a non-governmental organisation providing harm-reduction services to PWID in Pakistan.

The study used routinely collected programmatic data from January 2012 through December 2023, with follow-up information available through July 2024.

The repository accompanies the manuscript:

> **HIV incidence trends and associated risk factors in a national cohort of people who inject drugs attending harm reduction services in Pakistan**

## Data availability

The underlying individual-level dataset is **not included in this repository**.

The data were collected and are held by Nai Zindagi Trust and contain sensitive information relating to human participants. The dataset is subject to restrictions on redistribution and public release under the applicable data-sharing arrangements.

The individual-level data therefore cannot be deposited in a public repository or redistributed by the authors.

Researchers wishing to request access to the underlying data should contact **Nai Zindagi Trust** through the data-access mechanism described in the manuscript's Data Availability Statement. Requests for access are subject to the applicable ethical, legal, confidentiality and data-governance requirements.

No individual-level participant data, direct identifiers, or confidential information are included in this repository.

## Repository contents

The repository contains:

* `R/` — R scripts used for data preparation, cohort construction and statistical analyses
* `README.md` — description of the study, repository and data availability
* `Codebook for variable` — Data variable codebook 

## Study population

The source dataset contains routinely collected programmatic data from PWID accessing harm-reduction services provided by Nai Zindagi Trust across Pakistan.

Participants were eligible for the incidence analysis if they were HIV-negative at enrolment and had at least one subsequent HIV test during follow-up.

The analysis cohort and exclusions are defined in the corresponding R scripts.

## Statistical analysis

The repository contains code for:

* data cleaning and preparation;
* construction of the HIV incidence cohort;
* calculation of HIV incidence rates;
* person-time calculations;
* stratified analyses;
* assessment of temporal trends in HIV incidence;
* segmented/joinpoint regression analyses;
* sensitivity analyses; and
* generation of tables and figures.

The exact analytical methods and model specifications are described in the accompanying manuscript.

## Software

The analyses were conducted using **R**.

The principal R packages used in the analyses include:

* `readxl`
* `Epi`
* `survminer`
* `knitr`
* `ggfortify`
* `dplyr`
* `tidyr`
* `ggplot2`
* `survival`
* `segmented`
* `patchwork`
* `gtsummury`
* `biostat3`

The R version used for the final analysis will be specified here:

**R version:** R version 4.2.3 (2023-03-15 ucrt)

## Reproducibility

The analysis scripts require access to the restricted NZT dataset and therefore cannot be executed using the files in this repository alone.

The repository provides the analysis code and non-identifying documentation needed to understand the data processing and statistical analyses reported in the manuscript.

Because the underlying individual-level data cannot be publicly distributed, complete reproduction of the numerical results requires authorised access to the NZT dataset.

## Confidentiality

This repository does not contain:

* individual-level participant data;
* participant names or other direct identifiers;
* contact information;
* unique participant identification numbers;
* HIV test results linked to identifiable individuals;
* confidential geographical information; or
* other information that could reasonably identify individual participants.

Users should not add or commit restricted or confidential data to this repository.

## Licence

The code in this repository is made available under the **MIT License**.

The MIT License applies to the code contained in this repository only. It does **not** apply to the underlying NZT dataset, which remains subject to the data-access, confidentiality and governance arrangements of Nai Zindagi Trust.

## Contact

For questions regarding the analysis code or repository, please contact:

**Md Khadimul Anam Mazhar**
University of Bristol
khadimul.mazhar@bristol.ac.uk

For requests concerning access to the underlying NZT dataset, please contact **Nai Zindagi Trust (naizindagi@naizindagi.com)** through the data-access mechanism specified in the manuscript's Data Availability Statement.
