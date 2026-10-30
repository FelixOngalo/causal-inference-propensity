# Causal Inference in R: Propensity Scores, Weighting, and Matching

This project explores **causal inference in R** using simulated observational data with known confounding and a predefined true treatment effect. It demonstrates how statistical methods can help estimate causal relationships when treatment assignment is not randomised. The analysis implements propensity score modelling, inverse-propensity score weighting (IPW), and propensity score matching, then compares their estimated treatment effects against the known ground-truth effect. By evaluating estimation accuracy and the impact of confounding, the project illustrates the strengths, assumptions, and limitations of different approaches to observational causal analysis.

## Key Concepts
- Causal inference and counterfactual reasoning
- Confounding and treatment assignment
- Propensity score estimation using logistic regression
- Inverse-propensity score weighting (IPW)
- Propensity score matching
- Average Treatment Effect (ATE) estimation
- Bias and estimation accuracy compared with a known true effect

## Tools and Technologies
- **Language:** R
- **Methods:** Logistic regression, propensity scores, weighting, and matching
- **Data:** Simulated observational data with known treatment effects

## Learning Objectives
- Understand how confounding affects observational treatment-effect estimates.
- Estimate propensity scores and use them to adjust for observed confounders.
- Compare weighting and matching approaches.
- Assess estimator performance against a known causal effect.
- Understand the assumptions and limitations of propensity score methods.
