# AgriPolicy Intelligence Dashboard

A minimal, BINUS Online-inspired research dashboard prototype based on the paper **“Data-Driven Agricultural Economic Transformation through Integrated Information Systems and AI-Based Decision Support for Sustainable Regional Development in West Priangan.”**

## Preview

`https://fradozonelegacy.github.io/bagasykes/agri-policy/`

## Dashboard contents

- Research KPI cards for R-squared, F-statistic, and model significance.
- OLS coefficient chart based on the values transcribed in Table 1.
- Schematic locator for Cianjur in the West Priangan context.
- VIF diagnostics chart.
- Qualitative agricultural-productivity trend as described by the paper.
- Model-fit doughnut chart and data-transparency note.

## Research transparency

- The methodology describes an empirical focus on Cianjur Regency over 2010–2017.
- The map is a schematic locator, not a geographic boundary map.
- The productivity trend is qualitative and is not a reconstruction of annual numeric observations.
- Table 1's coefficients differ from values in the surrounding narrative. Confirm the original STATA output before relying on the coefficients.
- The dashboard is a research prototype, not an official government system. Statistical associations should not automatically be interpreted as causal effects.

## Technology

Static HTML, CSS, and JavaScript; Chart.js loaded from a CDN. No build step required.
