# Modern Meta-analysis for Agri-food Evidence Synthesis

Training materials developed for EU-NESA COST Action CA23107.

## Course structure

The course follows a question-first workflow:

**question → estimand → compatible evidence → effect size → model → heterogeneity → dependence → moderators → robustness → interpretation**

Modules 0–3 form the introductory core. Modules 1–3 are presentation-ready teaching decks with presenter notes, conceptual graphics, R demonstrations, participant exercises and worked solutions.

## Render the site

From the project root:

```bash
quarto preview
```

Slides can also be rendered individually, for example:

```bash
quarto render slides/01-effect-sizes.qmd
```

## Core software

The practicals use R and `metafor`. `tidyverse` is used where helpful for data handling.

```r
install.packages(c("metafor", "tidyverse"))
```

## Teaching data

`data/teaching/soil_carbon.csv` is a **synthetic teaching dataset**. It is intended to demonstrate the workflow and must not be presented as empirical evidence.

## Modules

- Module 0 — From question to meta-analysis
- Module 1 — Effect sizes
- Module 2 — Your first meta-analysis
- Module 3 — Understanding heterogeneity
- Module 4 — Dependence and multilevel meta-analysis
- Module 5 — Meta-regression
- Module 6 — Sensitivity analysis
- Module 7 — Reporting and publication bias
- Module 8 — Interpretation for decisions

## Licence

Add the licence agreed with EU-NESA/COST before public release. For openly reusable teaching materials, CC BY 4.0 is a suitable option if compatible with the Action's requirements.

## Modules 7–8 completed

The course now includes the final modules on missing evidence/reporting bias and decision-relevant interpretation, with presenter notes, exercises and worked solutions. Module 7 deliberately treats funnel plots, regression tests and trim-and-fill as limited diagnostics rather than definitive tests/corrections for publication bias. Module 8 returns to the estimand and integrates magnitude, uncertainty, heterogeneity, robustness, reporting bias and transportability into a final evidence statement.
