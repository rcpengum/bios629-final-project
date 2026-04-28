# BIOS 629 Final Project

## Machine Learning Improves Survival Prediction in NSCLC

Ruicong Peng  
University of Michigan

## Project Summary

This project evaluates whether machine learning models improve survival prediction in non-small cell lung cancer (NSCLC) by integrating:

- Clinical features
- Genomic mutation data
- NLP-derived radiology features

Models compared:

- Cox proportional hazards model
- Random Survival Forests (RSF)
- XGBoost Survival Model

## Key Results

- Clinical only: C-index = 0.655
- Clinical + Genomic: 0.688
- Clinical + Genomic + NLP: 0.716
- RSF: 0.723
- XGBoost: 0.739

## Repository Contents

- Final-project.Rmd
- Final-project.pdf

## GitHub Repository

[Source Code Repository](https://github.com/rcpengum/bios629-final-project)

---

## Team

- Ruicong Peng • University of Michigan

Patient-level MSK-CHORD data are available through [cBioPortal](https://www.cbioportal.org/) under controlled access. Analysis code is freely available in this repository.

Questions? pruicong@umich.edu
