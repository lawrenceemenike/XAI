# XAI  
Repository for Model-Agnostic Techniques in Explainable AI (XAI).  

## Model-Agnostic Techniques  
This repository explores various **local and global** model-agnostic XAI techniques using an **XGBoost model** trained on a dataset from the **SHAP library**.  

### Local Explanation Techniques  
Used to understand individual predictions.  
- **LIME** – Local Interpretable Model-Agnostic Explanations for instance-level insights.  
- **Shapley Values** – A game-theoretic approach to fairly distributing feature contributions.  
- **SHAP (SHapley Additive exPlanations)** – A unified framework combining Shapley values with visualization tools.  
- **Individual Conditional Expectation (ICE)** – Instance-specific effect of a feature on model predictions.  
- **Anchor** – High-precision rule-based explanations for local model behavior.  

### Global Explanation Techniques  
Used to interpret the model as a whole.  
- **Partial Dependence Plots (PDPs)** – Shows how a feature affects predictions on average.  
- **Accumulated Local Effects (ALE)** – Accounts for feature dependencies while measuring global impact.  
- **Feature Importance (SHAP-based)** – Ranks features based on their contribution to predictions.  
- **Global Surrogate Models** – Trains a simpler, interpretable model to approximate the complex model.  

## Notebooks  
📂 **local_explanations.ipynb** – Implementation of local XAI techniques.  
📂 **global_explanations.ipynb** – Implementation of global XAI techniques.  

