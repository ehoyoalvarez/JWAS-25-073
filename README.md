# JWAS-25-073
This repository contains the R Markdown file (`analysis.Rmd`) used for all statistical analyses described in the manuscript:
Hoyo-Alvarez et al. (2025). *Cardiac activity cessation during slaughtering combinations in farmed European seabass*. Submitted to the Journal of the World Aquaculture Society (ID: JWAS-25-073).
---

## 📂 Repository contents

- `analysis.Rmd`: Fully commented R Markdown script performing the statistical modeling and analyses for the study.

## 📊 Description of analyses

The R Markdown performs:
- Generalized Linear Models (GLMs) on time-to-cardiac-cessation data, with Poisson or quasi-Poisson error structures depending on overdispersion.
- Linear Mixed-Effects Models (LMMs) for repeated heart rate measurements to assess heart rate stabilization after pre-slaughter ice immersion.
- Post-hoc comparisons with Tukey HSD corrections to control Type I error rates.

All models and justifications are fully documented in the Rmd.

---
## 📁 Data availability

The datasets used in this analysis are not publicly available within this repository, as they contain individual-level data. However, they can be made available upon reasonable request to the corresponding author.

Please contact [ehoyo@imedea.uib-csic.es] (mailto:ehoyo@imedea.uib-csic.es) to request access to the data

---

## ✅ Requirements

The R script uses the following R packages:

- `readxl`
- `dplyr`
- `car`
- `agricolae`
- `multcomp`
- `lme4`
- `lmerTest`
- `emmeans`

These can be installed with:

```r
install.packages(c("readxl", "dplyr", "car", "agricolae", "multcomp", "lme4", "lmerTest", "emmeans"))
```


