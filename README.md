# HouseInc measurement invariance

R code and figures for a measurement invariance analysis of the HouseInc Multinational Survey (eight European countries).

## Data

HouseInc Multinational Survey dataset (anonymised), Zenodo, https://doi.org/10.5281/zenodo.20538396 (CC BY 4.0).
The script downloads the data automatically.

## Requirements

R 4.5.2 with lavaan 0.7.3, semTools 0.5.10, data.table, arrow, readxl, jsonlite, psych, MASS, ggplot2 and openxlsx (missing packages are installed by the script).

## Code flow

| Step | Content |
|---|---|
| 00 | Data download and variable inventory |
| 01 | Item recoding, response distributions, polychoric correlations |
| 02 | Ordinal CFA of competing factor structures by country |
| 03 | Multi-group measurement invariance (configural to scalar) |
| 04 | Partial scalar invariance and country means |
| 05 | Two-stage latent means on the stratified subsample |
| 06 | Equal-variance sensitivity and rank uncertainty |
| 07 | Leave-one-country-out and alternative anchor sets |
| 09 | Further robustness checks, district heating (MIMIC), bootstrap |
| 10 | Bootstrap repeating the intercept selection, one-stage estimation |
| 11 | Fit of partial models, excluded items, affordability-only bootstrap |
| 12 | Remaining non-invariance after the partial release |
| 08 | Tables and figures (run last) |

Completed steps are skipped on re-run; the bootstrap steps are long but resumable.

## Figures

`Fig1`–`Fig3` in PDF and 1200 dpi TIFF.
