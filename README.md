# Examples of work
These are examples of my previous work that are relatively easy to show onlne. Please see below for different categories and brief explanations.

## Design of Experiments/Clinical Trials

### D-optimal Designs for Logistic Regression using a Genetic Algorithm
Dopt_logistic.pdf
Dopt_logistic_presentation.pdf

Logistic regression is a popular model for a binary outcome. While
locally D-optimal designs can be found analytically for the case of a
linear predictor, adding a quadratic term or constricting the design
interval makes finding the optimal design more challenging. In most
of these cases, there is no known analytical result. We use a genetic
algorithm to find locally D-optimal designs for linear and quadratic
models on any design interval. We are able to confirm previous results
and find new designs in several cases.

### Bayesian Monitoring for Group Sequential Trials
bayes_group_sequential_presentation.pdf

Presentation on Bayesian adaptive trials.

### Analysis of Encouragement Trials
encouragement_trials_explainer.pdf

Many studies with human subjects can be difficult or even unethical to conduct under normal circumstances. One issue is non-compliance, i.e. assignment of subjects to treatment does not ensure that the treatment is actually received. Another issue occurs when there is evidence that the treatment under consideration is clearly beneficial. Is it ethical to withhold this treatment for the sake of creating control group? These problems can be alleviated if the assignment, or encouragement, to a treatment and the actual receipt of the treatment are considered separately. In this arrangement, there are now two effects for the analyst to consider. First, we must consider the effect of encouragement on the receipt of the treatment. Secondly, but most importantly, we are interested in the direct effect of the treatment on the outcome. Trials that are designed to address these issues are called encouragement
trials. Imbens, Rubin, and others have developed a Bayesian based methodology for analyzing encouragement trials by treating encouragement as an instrumental variable.We first review the fundamental concepts of instrumental variables and then review the Bayesian methodology for estimating the direct causal effects of treatments


## Survival Analysis

### Time to PrEP Uptake for Youth at Risk for HIV
time_to_prep.pdf

Pre-exposure prophylaxis (PrEP) is a drug that can significantly reduce the risk of
getting HIV from sex or from injection drug use. This analysis assesses factors related to the time to PrEP uptake for the HIV- cohort who have not previously used PrEP. Various survival analysis techniques such as Kaplan-Meier estimates, log-rank tests, and Cox proportional hazards models were used to determine the effect of the intervention  and several risk factors on PrEP uptake. The analysis suggests that PrEP uptake had more to do with demographic factors than with the study intervention.

### Bayesian Analysis of Time to Seroconversion
bayes_time_to_seroconversion.pdf

Seroconversion is process by which HIV antibodies become detectable in the
blood. Therefore, seroconversion can be a proxy for HIV infection and it is
useful to know how time to seroconversion varies between different groups
and risk factors. However, seroconversion is relatively rare event and traditional survival methods can struggle to produce good estimates, especially for interval estimates. Therefore, Bayesian accelerated failure time models with informative priors from the literature were used to analyze the data. The Bayesian models provided much stable estimates for the regression coefficients, especially when compared to a Frequentist Weibull model.

## Structual Equation Models

### Structural Equation Modeling for HIV Stigma, Clinical Utilization, and Viral Suppression
sem_HIV_presentation.pdf
sem_prelim_analysis.pdf

HIV-related stigma can lead to fear of accessing services and ultimately lead to a lower chance of viral suppression. In this presentation of my work in progress analysis, I give background details about HIV, discuss possible issues with the data introduce a framework for structual equation modeling, and use that framework to analyze the data. The file sem_prelim_analysis.pdf contains my R code.

### Specifying Covariance Models using Path Diagrams
path_models_presentation.pdf

A seminar presentation I gave on the basics of structual equation modeling.

## Bayesian

### Bayesian Linear Regression for Big Data
bigdata_bayes_regression_presentation.html

A short presentation on how to do Bayesian regression when the data does not fit into memory.

### Sampling from the Banana Distribution
MCMC_banana_distribution.pdf

I implemented 3 ways of sampling from the "banana" distribution: direct sampling, Gibbs sampling, and the Metropolis algorithm. 


