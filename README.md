# AB-Testing-Case-Study

This Python script is designed to conduct a simulated A/B test, a commonly used method in statistics and data science for comparing two versions of a single variable. The objective is to determine which version performs better. This script serves as a practical case study to showcase A/B testing.

## Business Objective
Determine whether the new button ("Enroll Now") has a higher click-through rate than the old button("Secure Free Trial").

## Method
Utilizes numpy and pandas libraries to generate random binary click data (1 = click, 0 = no click).<br>
Creates two datasets: df_exp for the experimental group and df_con for the control group.<br>
Each group has 1000 samples with different click probabilities (0.5 for exp and 0.2 for con).<br>
Merges the data into a single DataFrame df_ab_test for analysis.<br>

## AB Testing Concepts:
Primary metric: Click-through rate (CTR) <br>
 Hypothesis:<br>
Null hypothesis (HO): CTR of control (Secure Free Trial) = CTR of experimental (Enroll Now)',<br>
Alternative hypothesis (H1): CTR of control != CTR of experimental,<br>
 Statistical significance level (alpha): 0.05 (5%),<br>
 Minimum detectable effect (delta): 10%,<br>
 Statistical test: Two-sample Zest<br>

## Conclusion:
 Based on the AB test results, the new button ("Enroll Now") has a statistically significant and practically
 significant higher CTR than the old button ("Secure Free Trial"). The business can confidently implement
 the new button in production.
 <br><br>

_This case study illustrates the effective use of A/B testing in digital marketing, website optimization, and user experience research for data-driven decision-making._
