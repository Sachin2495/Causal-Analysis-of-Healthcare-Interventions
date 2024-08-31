# Causal-Analysis-of-Healthcare-Interventions
This project aims to assess the causal impact of healthcare interventions (e.g., a new treatment, a public health campaign, or a policy change) on patient outcomes using Causal Machine Learning (Causal ML). The goal is to estimate the effect of the intervention on health outcomes and ensure that the findings are robust against potential biases.

# Steps

1. Data Preparation:

Load and Explore Data:
Load the healthcare dataset and explore the basic statistics.
Handle missing values and ensure data consistency.
Feature Engineering:
Create relevant features such as a binary treatment variable indicating whether a patient received the intervention.
Consider confounding variables that might affect both the intervention and the outcome.
2. Causal Inference Model:

Define the Causal Model:
Identify the treatment, outcome, and confounders.
Create a causal model using dowhy or causalml.
Estimate the Causal Effect:
Use methods like Propensity Score Matching, Doubly Robust Estimation, or Instrumental Variables to estimate the causal effect.
Interpret the results, understanding the magnitude and direction of the effect.
Refutation Analysis:
Conduct robustness checks using methods such as placebo tests, bootstrap refutation, or subset validation.
Ensure that the estimated causal effect is not driven by biases or random chance.
3. Visualization and Reporting:

Visualize Findings:
Use plots to illustrate the distribution of outcomes for treated vs. control groups.
Visualize the estimated causal effect and confidence intervals.
Reporting:
Summarize the findings in a clear and concise report.
Discuss the implications of the causal analysis on healthcare policy and practice.
Provide recommendations based on the results.


                          Age  Comorbidity  Intervention     Outcome
Mean                52.881000      0.51000      0.502000   72.854195
Median              52.500000      1.00000      1.000000   73.179897
Standard Deviation  20.958915      0.50015      0.500246   11.622452
Minimum             18.000000      0.00000      0.000000   32.933996
Maximum             89.000000      1.00000      1.000000  109.850075
Range               71.000000      1.00000      1.000000   76.916079
