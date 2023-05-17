# cucovid19_hcw_longitudinal

This repository contains the code and documentation for the analysis of mental health trends among healthcare workers (HCWs) in Hong Kong. The study is based on three waves of survey results from the CU-COVID19 study, a multi-center, web-based observational cohort study investigating the incident mental morbidity of COVID-19 survivors, healthcare workers, and the general Hong Kong population.

Primary Objectives
The primary objectives of this study are:

1. To examine longitudinal mental health growth trends in healthcare workers over an 18-month period during the pandemic.
2. To identify distinct classes characterized by different mental health growth trends.
3. To investigate whether infection worries and workplace difficulties are associated with latent class membership and variation in growth trends within each class.

To achieve these objectives, Latent Class Growth Analysis (LCGA), Confirmatory Factor Analysis (CFA), and individual regression will be performed.

Repository Contents

CFA_stronginvariance_17May23.inp: MPlus input file for CFA with strong invariance
CFA_weakinvariance_17May23.inp: MPlus input file for CFA with weak invariance
CFA_unconstrained_17May23.inp: MPlus input file for CFA with unconstrained model
LCGA_class_enumeration_17May23.inp: MPlus input file for LCGA class enumeration
LCGA_covariates_17May23.inp: MPlus input file for testing the effects of transmission worries and workpalce difficulties on class membership and growth factors
individual_regression_17May23.ipynb: Python notebook for individual linear regression
