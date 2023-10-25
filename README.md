# Mushroom Dataset Analysis

## Introduction

This repository focuses on the analysis of the **Mushroom** dataset. Our goal is to identify dangerous mushrooms, ensuring that individuals can differentiate between toxic and edible species.

## Key Features of the Dataset

- **Dataset Size**: 8124 observations
- **Variables**: 23
- **Data Type**: Character (with various attributes represented by specific letters)

## Analysis Overview

1. **Data Overview**: A concise examination of data metadata, including non-null values, data types, and memory usage.

2. **Descriptive Statistics**: A comprehensive description of the dataset, which includes the count, mean, standard deviation, minimum value, maximum value, and quartiles.

3. **Correlation Analysis**: Investigated relationships between variables, notably between `gill-attachment` and `veil-type`.

4. **Visualization**: Generated bar plots to understand variable distributions, notably the target value `class` and its correlations with other attributes.

5. **Modeling**: Employed a decision tree model to fit the data, identifying key attributes contributing to the edibility of mushrooms.

## Key Findings and Recommendations

- **Odor** emerged as the most crucial determinant for mushroom edibility.
- The likelihood of a mushroom being poisonous was determined through various nodes in the decision tree, with a starting probability of **48%** at the root node.
- The analysis suggests the potential for a **Foraging App**, guiding users to edible mushrooms in their vicinity.

## Conclusion

Our analysis provides invaluable insights into mushroom edibility, guiding individuals in making safer choices while foraging or purchasing mushrooms.

