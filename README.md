# Explainable AI for Airline Passenger Satisfaction
Second assignment of the course Advanced Topics in Machine Learning (MSc in Artificial Intelligence, 1st year, 1st semester)

## A Little Context
### Overview
This project explores the implementation of Explainable Artificial Intelligence (XAI) techniques in a supervised learning framework, using the Airline Passenger Satisfaction dataset. The objectives include:

Employing pre-modeling techniques to analyze feature importance.
Utilizing in-modeling techniques to leverage interpretable models for transparency.
Applying post-modeling techniques like SHAP and PDP to demystify black-box models.
Assessing the quality of explanations through fidelity scores and visualizations.
By systematically integrating these approaches, the project provides insights into how XAI can enhance the interpretability and trustworthiness of machine learning models.

### Content
The repository includes:

Notebooks Folder: Jupyter notebooks detailing different tasks of the project.
README File: This document, summarizing the project objectives and structure.
Requirements.txt: To run the notebook

### Objective: Conduct feature importance analysis and dataset preprocessing.

Understanding and trusting machine learning models is crucial, especially in fields with high stakes or user-centric applications. This project investigates a systematic framework for explainability by integrating:

Pre-Modeling Techniques: Feature analysis and preprocessing to improve initial interpretability.
In-Modeling Techniques: Intrinsically interpretable models, such as Decision Trees, for direct insights into predictions.
Post-Modeling Techniques: Advanced methods like SHAP values, Partial Dependence Plots, and Anchor Explanations to clarify the decision-making process of black-box models like XGBoost.

### Key Insights

- Feature Importance: Attributes such as flight distance, online check-in, and in-flight service play a pivotal role in predicting passenger satisfaction.
- Model Comparison: While glass-box models provide inherent interpretability, black-box models achieve superior performance, necessitating post-hoc explainability methods.
- Explanation Quality: Most explanations were accurate, but challenges remain in simplifying complex decision boundaries, especially in edge cases.

### Usage
To run the application:

Clone this repository and navigate to the project directory.
Install dependencies listed in requirements.txt.
Run the notebook.
