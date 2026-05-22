
# Explainable AI (XAI) for Sensor-Based Ecological Predictions

An advanced computational biology project implementing **SHapley Additive exPlanations (SHAP)** to interpret a 'black-box' Random Forest model predicting freshwater biodiversity status. 

## 🔬 Computational Context
In ecological modeling, machine learning models often lack transparency, preventing field biologists from trusting automated decisions. This project bridges the gap between high-accuracy machine learning and ecological theory by applying Explainable AI (XAI). Instead of just outputting a probability score, this pipeline mathematically attributes the precise credit or blame to each environmental sensor (pH, Oxygen, Nitrates) for every single ecosystem assessment.

## 💡 XAI Features Deployed
* **Global Interpretability (Summary Plots):** Maps out the overall directional impact of high and low feature values across the entire population matrix.
* **Local Interpretability (Waterfall Plots):** Conducts a site-by-site post-mortem analysis, visualizing exactly how a specific sensor spike or drop altered the model's prediction threshold.
