# Data Analysis Portfolio

This repository contains information on all three projects completed during my time in Practical Data Analysis, a course required for my program.

A brief description of each project is outlined below, as well as a link to the repository:

### Project One

This project aims to explore the effects of smoking during pregnancy (SDP) and environmental tobacco smoke (ETS) exposure on adolescent self-regulation, substance use, and externalizing. The data used from this project comes from two studies, <a href='https://pubmed.ncbi.nlm.nih.gov/27818283/'>one of which was published in 2016</a>. The data has not been made publicly available, but the information provided in this documentation will provide a thorough explanation of the data, while respecting data privacy. The code for this project will be provided, as well as summary tables that allow some insight into the data used.

The link to the repository is <a href='https://github.com/taramz/project_one'>here</a>.

### Project Two

This study utilizes a national dataset of 996 infants with severe Bronchopulmonary Dysplasia (sBPD) from 10 centers, focusing on demographics, diagnostics, and respiratory parameters at 36 and 44 weeks post-menstrual age to predict if an infant should receive a tracheostomy. Concerns arise from a disproportionate center representation, potential biases, and notable tracheostomy percentage variations among centers. Variable selection identifies significant covariates, emphasizing prenatal corticosteroids, small for gestational age (SGA), inspired O2, medication for pulmonary hypertension (PH), and invasive positive pressure. Correlation analyses guide the exclusion of correlated metrics, and missing data patterns prompt careful imputation considerations.

Fixed effects models and mixed-effects models, acknowledging center-level variation, reveal consistent predictors in both 36 and 44-week models. Evaluation metrics favor the 44-week model, indicating superior predictive accuracy, precision, and recall. Surprisingly, the addition of a random intercept for center minimally affects model performance on validation data, suggesting limited center-level variation. This study emphasizes the complexity of predicting tracheostomy in sBPD infants, providing direction for future predictive models for tracheostomy.

The link to the repository is <a href='https://github.com/taramz/project_two'>here</a>.


### Project Three

Empirical investigations often span two distinct populations—the study population and the target population. The alignment of these populations is challenging, especially when constructing predictive models intended for application in the target population. Discrepancies between them can compromise model efficacy, emphasizing the need for transportability analysis.

Datasets from the Framingham Study and NHANES are leveraged to explore cardiovascular disease (CVD) prediction across diverse populations. The Framingham Study, initiated in 1948, is a longitudinal cohort investigating CVD epidemiology and risk factors. NHANES evaluates the health and nutritional status of the U.S. population, integrating self-reported and comprehensive examination data.

Population disparities between Framingham and NHANES underscore the imprudence of extrapolating model performance across datasets. Transportability analysis becomes imperative to understand model generalizability. The Brier score, a metric for probabilistic predictions, is employed, but adjustments are made to evaluate transportability. Multiple imputation addresses NHANES' missing data, and gender-specific average Brier scores are computed.

The ADEMP framework guides simulation considerations, encompassing aim, data generating mechanism, estimand, methods, and performance measures. Simulation involves diverse parameter variations for gender-specific data generation, aiming to replicate NHANES demographics.

The evaluation of simulated datasets using bias and mean squared error reveals nuanced differences between genders. Optimal covariance values for minimizing bias and MSE differ for men and women. The Brier score comparison and summary statistics show congruence with NHANES for women but slight discrepancies for men, potentially attributed to data variability.

The data generation process incorporates missing variables, potentially contributing to disparities in Brier scores. Computational constraints limit simulations, raising the possibility of unstable estimates. These considerations highlight areas for refining the data generation process and underscore the importance of meticulous transportability analysis in model development and application across diverse populations.

The link to the repository is <a href='https://github.com/taramz/project_three'>here</a>.
