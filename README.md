# Survival-Analysis

> R packages: asaur, tidyverse, maxLik, survivalROC, glmnet
  
### Day 1: Censored duration

Linear Regression

Generalied Linear

1. Linear
  
2. Count data (e.g. Poisson, Binomial, Neg Origianl, Logistic)

### Day 2: Nonparameter answer of censored duration

#### [Lab 2](https://github.com/wulinghsuan/Survival-Analysis/blob/master/020-nonparam.pdf): rats example, the Xelox trial, the pancreatic dataset

One group: `KM` + `surv function` + `Median`

Two group or more: `Statistical function for comparisons` + `Logrank Test`

### Day 3: Cox Proportional Hazards (CPH)

#### [Lab 2 cont.](https://github.com/wulinghsuan/Survival-Analysis/blob/master/020-nonparam-cont.pdf): the pharmacoSmoking dataset

#### [Lab 3](https://github.com/wulinghsuan/Survival-Analysis/blob/master/030-Cox_Regression.pdf): rats example, the pharmacoSmoking dataset

Stratified Logrank Test 

Regression Analyst: Cox-Regression

Interpretation of model results

Predicting Survival: model base

Interaction Test

### Day 4: Model Building

#### [Lab 4](https://github.com/wulinghsuan/Survival-Analysis/blob/master/030-Cox_Regression.pdf): Nicotine Addiction

(Partial) Likelihood Ratio Test (LRT) 

→ p-value >= 0.05 Keep extra parameter

→ p-value <= 0.05 Stick with simple moodel

> anova(MA, MB)

Non-nested model: AIC

→ the lower the better

> AIC(MA), AIC(MB)

||LRT|AIC|
|---|---|---|
|nested model| V | V |
|non-nested model| X | V |

Nested model

### Day 5: 050-CPH-penalized

### Case Study: The Lung Cancer Dataset

### Case Study: [COVID-19](https://github.com/wulinghsuan/Survival-Analysis/blob/master/COVID-19.pdf)

[Data source](https://docs.google.com/spreadsheets/d/e/2PACX-1vQU0SIALScXx8VXDX7yKNKWWPKE1YjFlWc6VTEVSN45CklWWf-uWmprQIyLtoPDA18tX9cFDr-aQ9S6/pubhtml): Last update: 03/13/2020, 8:00 PM (EST)

- Y: Death_Status
- X: Age, Gender, Conuntry
