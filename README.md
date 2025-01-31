# Comparitive-Analysis-of-Tree-Based-and-Hill-Climb-Search-Based-CPDs-for-Evidential-Inferencing

This project presents a comprehensive analysis of postnatal depression using Probabilistic Graphical Models (PGMs), focusing on comparing Tree-Based and Hill Climb Search-Based Conditional Probability Distributions (CPDs). The goal is to understand and predict the risk factors associated with postnatal depression using Bayesian Network modeling.

## Key Features
- **Implementation of Bayesian Networks** for modeling postnatal depression factors.
- **Comparison** between Tree-Based and Hill Climb Search methods.
- **Variable elimination** and inference techniques.
- **Comprehensive analysis** of conditional probabilities.
- **Performance evaluation** using accuracy metrics.

## Dataset Description
The dataset comprises records collected from a medical hospital related to postpartum depression. Key attributes include:

- Timestamp
- Age
- Feeling sad or tearful
- Irritable towards baby & partner
- Trouble sleeping at night
- Problems concentrating or making decisions
- Overeating or loss of appetite
- Feeling anxious (target attribute)
- Feeling of guilt
- Problems of bonding with baby
- Suicide attempt

## Implementation Details

### Models Used

#### Tree-Based Bayesian Network
- **Root node-based structure learning**
- **Chow-Liu tree algorithm implementation**
- **Variable elimination for inference**

#### Hill Climb Search-Based Network
- **Score-based structure learning**
- **BIC score optimization**
- **Maximum Likelihood Estimation**

### Key Findings
The comparative analysis revealed:
- **Tree-Based model accuracy:** ~61.50%
- **Hill Climb Search-Based model accuracy:** ~99.59%
- Significant conditional dependencies between variables.
- Effective variable elimination ordering for inference.

### Inference Results (Conditional Probability Examples)

1. **Feeling Anxious given Age [30-35 years]:**
   - Not Anxious: 0.3514
   - Anxious: 0.6486

2. **Feeling Anxious given Overeating/Loss of Appetite:**
   - Not Anxious: 0.3530
   - Anxious: 0.6470

3. **Feeling Anxious given Age [25-30 years] and Feeling of Guilt:**
   - Not Anxious: 0.1079
   - Anxious: 0.8921

## Conclusion
This project highlights the use of Probabilistic Graphical Models (PGMs) for understanding and predicting postnatal depression. The analysis compares two structure learning methods: Tree-Based Bayesian Networks and Hill Climb Search-Based Networks. The results show a significant difference in accuracy between the two models, with the Hill Climb Search-Based Network achieving a much higher accuracy. The study also provides valuable insights into the conditional dependencies among variables and demonstrates the effectiveness of variable elimination for inference. Overall, this project contributes to understanding the application of PGMs in healthcare, especially in predicting mental health conditions such as postnatal depression.
