# Feature Selection
process of selecting features(variables) for ML model

packages
- numpy, pandas, matplotlib
- scikit-learn

## Contents
|                       |                                          |
| --------------------- | ---------------------------------------- |
|                       |                                          |
| 2. FeatureSelection   |                                          |
|                       |                                          |
| Filter Methods        |                                          |
| 3. Basic              |                                          |
| 4. StatisticalMeasure |                                          |
|                       |                                          |
| 5. Correlation        |                                          |
| Wrapper Methods       | step Forward/backward; Exhaustive Search |
|                       |                                          |
| Embedded Methods      |                                          |
| 7. Lasso              |                                          |
| 8. LinearModels       |                                          |
| 9. Trees              |                                          |
|                       |                                          |
|                       |                                          |

## Overview

feature selection -> search new subsets and evaluate

### Filter 
rely on characteristics; less computation and quick to implement; model agnostic

STEPs
1. rank features : independently
2. select the highest features : not consider 

Ranking Criteria :
- FisherScore(chi-square)
- anova(univariate parametric test)
- Variance(constant, quasi-constant)

Multivariate 

### Wrapper 
use predictive ML model to score; train in each feature subset;

### Embedded 
consider interaction between "model & feature"