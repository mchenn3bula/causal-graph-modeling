# Causal Graph Modeling 🔄

## Overview 📊
This project explores causal relationships through Directed Acyclic Graphs (DAGs) and demonstrates stratified blocking methods for improved treatment effect estimation.

## Key Techniques 🔍
- **DAG analysis** for identifying causal pathways
- **Backdoor path** identification
- **Confounder adjustment** strategies 
- **Stratified blocking** for variance reduction
- **Heterogeneous treatment effect** estimation

## Mathematical Framework 🔢
The analysis implements several important concepts:

### Backdoor Criterion
For identifying a set of variables Z sufficient for adjustment:
- Z blocks all backdoor paths from treatment T to outcome Y
- Z contains no descendants of T

### Block-specific Treatment Effects
$$\tau_x = E[Y(1) - Y(0) | X=x]$$

### Variance of Blocked Estimator
$$Var(\hat{\tau}_{block}) = \sum_{x} \frac{n_x^2}{n^2} Var(\hat{\tau}_x)$$

## Skills Demonstrated 💪
- Causal graph construction and interpretation
- Identification of potential sources of bias
- Conditional independence testing
- Heterogeneity analysis across subgroups
- Advanced statistical modeling in Python
- Strategic data stratification for improved inference

## Project Significance 🌟
This project demonstrates the ability to translate complex causal relationships into actionable analytical strategies, crucial for decision-making in data-rich environments where identifying true causal effects is essential.
