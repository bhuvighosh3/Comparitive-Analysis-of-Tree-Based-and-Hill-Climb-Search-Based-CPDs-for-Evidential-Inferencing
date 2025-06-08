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
- **Tree-Based model accuracy:** ~93.67%
- **Hill Climb Search-Based model accuracy:** ~97.25%
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
- This project demonstrates the use of Probabilistic Graphical Models (PGMs) to predict postnatal depression.
- **Hill Climb Search-Based Network** outperformed the **Tree-Based Bayesian Network** in accuracy (~97.25% vs. ~93.67%).
- Significant conditional dependencies were found between variables.
- Effective variable elimination techniques were applied for inference.
- The analysis highlights PGMs potential in healthcare, particularly for predicting mental health conditions.
