# DS3000-Project
Repo for DS 3000 Project

This project’s central motivation is to use data to evaluate the effectiveness of existing approaches to overcome the challenges associated with cancer treatment, as well as to discover causal and consequential relationships between different aspects of cancer treatment plans, which we hope could potentially improve treatment strategies. The two key questions that drive our investigation are:

Question 1. How do different treatment approaches correlate with patient survival rates for specific cancer types?
Question 2. Can we predict the most eﬀective treatment plan based on patient characteristics and cancer type?

The purpose of this question is to find a quantifiable relationship between various treatment practices and patients’ outcomes, differentiating by cancer type. Through these correlations, we hope to understand which treatments are the most promising for specific cancer types. To answer this question, we will:

1) Analyze data from The Cancer Imaging Archive (TCIA) and the National Cancer Institute's Genomic Data Commons:
Collect treatment data (type of treatment, duration, dosage, etc.)
Collect patient outcome data (survival rates, disease progression)
Categorize data by specific cancer types

2) Use statistical analysis techniques such as:
Multivariate regression:
method of modeling multiple responses, or dependent variables, with a single set of predictor variables. For example, we might want to model both math and reading SAT scores as a function of gender, race, parent income, and so forth [source]
=> allows to control for intersecting factors: age, stage of cancer, etc.
Possibly: analyzing subgroups: are certain treatments more effective for specific patient demographics or cancer types?

3) Visualize the results:
Scatter Plot: treatment duration vs. patient survival time
=> identify optimal treatment durations & any diminishing returns from prolonged treatment
(when benefits of continuing a cancer treatment decrease over time, while the risks and side effects may increase)
Pie Chart: treatment distribution
=> proportion of patients receiving each type of treatment; gives context for the prevalence of anyt treatment approaches
Heat maps: Effectiveness of treatments for various cancer types
X-axis: treatment approaches (Chemotherapy/Radiation/Immunotherapy/Surgery);
Y-axis: cancer types (Lung/Breast/Colon/Prostate/Melanoma);
Color intensity will represent the effectiveness of the treatment, for example, n-year survival rate or some other measure of treatment success




