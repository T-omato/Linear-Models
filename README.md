# Linear-Models
This is the first repository. Here I show fundamental Statistical knowledge bottom-up. Bottom-up is an ecological term, analogically I mean that this repository is for showing how I went from learning the essentials to more sophisticated analysis:

This README.md file is to specify the order in which "statistical growth" should be viewed (or as a index of statistical analysis complexity) as well as a brief summary of contents for each repository.

All the data in "Linear Models" responds to the Normal Family of distributions. 

#1 Simple Linear Regression
Simple variable analysis, where there is only 1 variable to explain the data. Density plots describing median, means, modes. Simple linear model proposals and Assumption corroboration. 

#2 PCA Analysis
In this data set there are 3 explanatory variables. 
Variance Inflation Factor is studied. Principal Component Analysis is also analyzed.
Exclusion of variables and model selection using Aikaike and Log(Likelihood) analysis. 
3D scatter plot showing how the data responds to the explanatory variables

#3 Variable Interaction
Unbalanced design. Principle of Homoscedasticity isn't met and Variance is modelled in order to get the "best" model.

#4 Aleatory Effects
The first three statistical analysis only had fixed effects, now I contemplate the existence of aleatory effects. This brings up a very important statistical situation: Lack of independence between the data observations. Aleatory effects generate a correlation matrix between observations. This must be specified by the model. This can be done by declaring the aleatory effects of each individual (experimental unit) or by declaring a correlation matrix (marginal effects). Both analysis are correct, but the model to be chosen depends on the objective of the study. Aleatory effects makes the model specific for the individuals studied while marginal effects is more "general".

#5 Repeated Measurements
Here most of the data has been collected from a same individual. This violates the Independency between observation Assumption, since the data has been collected from a same individual the data is naturally correlated. In this analysis a patient was measured multiple times at different times. The data's co-variance matrix was modelled to specify this lack of independency. Different ways to model the co-variance matrix was used and the models were compared in the traditional fashion: AIC value and comparing Log(likelihood) values between models. 

