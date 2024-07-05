# Diabetes Risk Assessment using Bayesian Networks (pgmpy library)—project of Module 3 of FAIKR—Professor P.Torroni

# Evaluating Causal Bayesian Networks for Diabetes Risk Assessment

## Overview

This project evaluates the use of Causal Bayesian Networks (CBNs) for assessing diabetes risk. Using data from the Behavioral Risk Factor Surveillance System (BRFSS), we construct and analyze a network model to understand the factors influencing diabetes.

## Data Source

The dataset utilized in this study is derived from the BRFSS, a comprehensive health survey system collecting data from U.S. residents. The dataset includes 253,680 health assessments, covering a broad range of variables such as income, education, physical activity, and various health conditions.

## Methodology

### Network Definition

We constructed the Bayesian network using domain expertise to define the structure and parameters. Two parameter learning methods were employed:
- Maximum Likelihood Estimator
- Bayesian Estimator

### Analysis

The analysis included:
- **Markov Condition**: Examining conditional independencies in the network.
- **Active Trails**: Identifying influential paths between variables.
- **Markov Blanket**: Determining the minimal set of variables that shield a variable from the rest of the network.

### Inference Techniques

We applied both exact and approximate inference methods, including:
- Forward Sampling
- Rejection Sampling

The project also explored the trade-offs between computational efficiency and accuracy in probabilistic modeling.

## Key Findings

- Lower income is associated with higher diabetes risk due to reduced access to healthy foods and healthcare.
- High blood pressure and cholesterol significantly increase the risk of developing diabetes.
- Smoking has a minimal effect on diabetes risk in this dataset, likely due to the low-confidence edge determined by domain experts.
- Heavy alcohol consumption did not show a significant association with diabetes, potentially due to low prevalence in the dataset.

## Conclusion

The study demonstrates the robustness of Bayesian networks in modeling complex health-related data and underscores the importance of considering both method and data nature in probabilistic modeling.

