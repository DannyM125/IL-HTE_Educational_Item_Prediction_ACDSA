# IL-HTE_Educational_Item_Prediction

The success of educational interventions is generally assessed through numerical approaches accounting for only total student scores. This approach, however, fails to consider item-specific effects, which can offer a more fine-grained perspective on the impact of the intervention. This work comparatively evaluates the ability of artificial neural network (ANN) approaches to recognize and evaluate heterogeneous treatment effects (HTE), which can allow for nuanced assistance that can better cater to individual student needs. Our work conducts a comparative analysis of artificial neural networks, specifically deep neural networks (DNN) and convolutional neural networks (CNN), to a traditional baseline explanatory item response model (EIRM).

In the SHAP and feature importance analysis of this study, we found that factors like socioeconomic status and home language had somewhat strong correlations with item-level predictions, on top of the usual high-ranking correlators like baseline test scores. 

This study concludes that a neural network-based approach obtains higher accuracy and proves to be as competitive as traditional methods on most measured metrics. These results indicate that robust, complex modeling techniques such as neural networks can have utility in prediction in the space of educational interventions. Identifying both home language and socioeconomic status as important predictors can help policymakers better understand the range of student characteristics associated with item-level performance and inform more targeted educational interventions. For example, these findings could motivate additional investigation into language-support resources and interventions for students from lower-SES backgrounds. Although these relationships do not establish causation, they demonstrate how combining interpretable statistical models with flexible machine-learning approaches can provide a more nuanced understanding of educational disparities and could help guide future research and resource allocation.


# Code Structure
This repo contains scripts for training machine learning models to predict Item-Level Heterogeneous Treatment Effects (IL-HTE) using Logistic Regression, DNN, and CNN.

Each script:
1. Trains and saves a model to models/.
2. Calculates performance metrics (Accuracy, F1, MSE, AUC ROC).
3. Generates feature importance charts (SHAP, Absolute Coefficient Value).
