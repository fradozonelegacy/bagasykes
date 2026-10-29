# Health Burden Intelligence Dashboard

A lightweight research dashboard for exploring the Health Burden Index (HBI) and a 38 × 38 spatial weight matrix for Indonesia's 38 provinces over 2017–2024.

## Important data note
The uploaded paper by Wicaksono & Pradana (2026) describes a panel of 38 provinces over 2017–2024 (304 province-year observations) and reports associations from pooled OLS, fixed effects, random effects, a lagged robustness specification, and Java/outside-Java comparisons. It does not provide an explicit, downloadable 304-row numeric panel in the manuscript text nor report an estimated spatial econometric model.

Accordingly, charts and province-year values in this prototype are **illustrative demonstration data**, not the study's original observations, calculated HBI values, estimated spatial weights, or spatial model results. The 38 × 38 matrix heatmap is a structural illustration. Replace these with verified province-year data, validated geography/coordinates, and reproducible model estimates before using results in research or policy.

## Dashboard features
- Year, region-group, and indicator filters
- Interactive chart and province table
- Export of the filtered illustrative data as CSV
- A 38 × 38 spatial-weight matrix illustration
- HBI formula, spatial-lag explanation, and candidate Spatial Durbin Model framework
- Summary of source-paper findings and limitations

## HBI method shown
Min–max normalization to a 0–1 scale, reversed normalization for beneficial indicators, then an equally weighted arithmetic mean:

`HBI_{it} = (1/n) \sum_k X^*_{kit}`

The paper's formula section refers to `n` indicators but does not enumerate the full component list explicitly alongside the formula; confirm the operational definition against the source dataset before constructing the index.

## Deploy
This dashboard is a static website in `health-burden/index.html`. It is intended to be served by GitHub Pages with base path `/health-burden/` from the repository's existing Pages deployment workflow.