# dds-expenditures-equity-analysis
Exploratory analysis of California DDS service expenditures using visualization, a permutation test, and regression to study demographic differences and age-cohort confounding.

## What I analyze

The workflow has three components:

1. Exploratory analysis
   - Median expenditures by ethnicity (log-scale visualization)
   - Expenditures vs age (hexbin + log scale)
   - Within-age-cohort comparisons to reduce confounding

2. Permutation test (within a fixed age cohort)
   - Compare mean expenditures for Minority vs Non-minority within age 13 to 17
   - Build a null distribution by shuffling group labels

3. Regression model (adjusted associations)
   - Model log(Expenditures) as a function of age cohort, gender, and ethnicity
   - Report coefficient estimates and uncertainty (including a bootstrap SE example)

All results are descriptive associations and should not be interpreted as causal effects.
