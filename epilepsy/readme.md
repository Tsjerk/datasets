# Epilepsy drug trial

A randomised clinical trial investigating the effect of an anti-epileptic drug.


## Format

A data frame with 236 observations on the following 6 variables.

- **subject** the patient ID, a factor with levels 1 to 59.
- **treatment** the treatment group, a factor with levels placebo and Progabide.
- **base** the number of seizures before the trial.
- **age** the age of the patient.
- **seizure.rate** the number of seizures (response variable).
- **period** treatment period, an ordered factor with levels 1 to 4.

## Details

In this clinical trial, 59 patients suffering from epilepsy were randomized to groups receiving either the anti-epileptic drug Progabide or a placebo in addition to standard chemotherapy. The numbers of seizures suffered in each of four, two-week periods were recorded for each patient along with a baseline seizure count for the 8 weeks prior to being randomized to treatment and age. The main question of interest is whether taking Progabide reduced the number of epileptic seizures compared with placebo.

### Reference
P. F. Thall and S. C. Vail (1990), Some covariance models for longitudinal count data with overdispersion. Biometrics, 46, 657–671.
Examples
