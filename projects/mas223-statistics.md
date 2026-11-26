# Applied Statistics in R
### Completed coursework · MAS223

Three assignments exploring uncertainty, regression, dimension reduction and classification.

| Study | Methods explored |
| --- | --- |
| House prices and height data | Descriptive analysis, visualisation, delete-one jackknife, bootstrap confidence intervals and linear regression |
| Milk-production dataset | Interaction/main-effects regression, diagnostics, prediction intervals, bootstrap-based error estimates and repeated cross-validation |
| Horse dataset | Standardised PCA, LDA, adjusted class priors, classification trees and pruning |

## What I practised
- Using R to move from exploratory plots to statistical models.
- Comparing model error with resampling and cross-validation.
- Interpreting regression terms and checking residual patterns.
- Working with dimension reduction, classification and confusion matrices.
- Writing an analytical report with tables and diagnostic figures.

## Project status
The original scripts and Assignment 2 report are preserved privately. Portfolio working copies have a configurable data path and documented dependencies.

The external datasets were not included in the upload, and no R runtime was available for this import. Numerical results have not been independently reproduced.

## Review and learning
Source review identified points to improve: the fixed bootstrap weighting should not be called adaptive .632+; PCA should be fitted on training observations for a clean predictive evaluation; and the pruning choice should be reconciled with the cross-validation result. The working copy corrects the bootstrap label while retaining its calculation. Further methodological changes would be a separate revision.

This page showcases completed coursework and the methods explored, with its validation limits stated. The statistical examples are educational.

[← Back to completed projects](https://github.com/Ginnnyyyy#completed-projects)
