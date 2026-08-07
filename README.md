# Missing Data in Machine Learning â€” Review and Reproducible Examples

A literature review and practical study of missing-data management for machine learning in health-related settings.

## Overview

The project connects statistical missing-data mechanisms with machine-learning practice. It discusses how missingness assumptions, imputation choices and evaluation design can change downstream conclusions.

## Contents

- `PapierRevueGestionDonneesmanquantes.pdf` â€” written review
- `Gestions de DonnÃ©es manquantes.pdf` â€” presentation slides
- `gestiondedonn-esmanquantesnotebook.ipynb` â€” computational examples

## Topics covered

- Missing completely at random, missing at random and missing not at random.
- Classical and model-based imputation strategies.
- Risks of leakage when imputers are fitted before the train/test split.
- Comparison of downstream predictive behavior under different preprocessing choices.
- Reproducible examples for selected claims from the review.

## Reproduction

Open the notebook in Jupyter and run the cells sequentially. Because the repository is primarily a review and teaching artifact, consult the notebook for the exact package versions and data-generation settings.

```bash
jupyter notebook gestiondedonn-esmanquantesnotebook.ipynb
```

## Status

Academic work completed in the context of machine learning for health at Sorbonne UniversitÃ©. It is not a clinical validation study.