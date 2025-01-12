# Histological Transformation Prognostic Index (HT-PI)
Time to transformation was defined as the was calculated from the date of FL diagnosis to the date of HT or last follow-up.
We used the Cox proportional hazards (PH) model for the univariate and multivariate survival analyses. We developed three models:
1) Firstly, we selected those genes with more than four mutations and performed one Cox univariable regression model for each gene to select those genes with a p-value = 0.1. After that, a multivariable Cox regression model with a backward strategy was performed (threshold of 0.05 in the p-value to retain the gene variable in the final model), so we obtained the “genetic” final model. *HIST1H1E* were statistically associated with a higher risk of HT, and mutations in *TNFRSF14* and *KMT2D* with a lower risk of HT and so were included into the model.
2) In parallel with this, we executed the “clinical” model including FLIPI through a Cox PH model.
3) Finally, we merged the genetic and clinical variables and obtained the “clinicogenetic” Cox PH model.

The probability of HT at 2 and 5 years for an individual patient can be calculated using the following
equations, derived from the Cox proportional hazards model:

(HT at 2 years) = 1 − 0.9954 exp (Prognostic Index)\
(HT at 5 years) = 1 − 0.9858 exp (Prognostic Index)

where Prognostic Index =\
1.639193 * FLIPI (high-risk) +\
1.383305 * *KMT2D* (not mutated) +\
1.615207 * *TNFRSF14* (not mutated) +\
2.102908 * *HIST1H1E* (mutated)
