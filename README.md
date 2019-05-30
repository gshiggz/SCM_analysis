# SCM_analysis

A quantitiatve look at a company's supply chain process utilizing a specific customer as a case study. Data was generated from 3 years of transactional data across 3 customer sites. The data utilized in this model has been cleaned to hide any propietary information. The goal of the analysis was to quantify features within the company's system and how these features attribute to orders being shipped "On Time" or "Late".

Model chosen was a Random Forest Classifier for its ability to capture non-linear relationships in the data as well as its built-in feature importance functionality for ease of explainability. The model's hyperparameters were optimized by way of RandomGridSearchCV 
Detailed feature explanation and visualizations was made possible by SHAP (SHapley Additive exPlanations) library. 
