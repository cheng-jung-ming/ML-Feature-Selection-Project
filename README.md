# 🎯 Predicting Customer Churn with Feature Ensemble Selection

> A feature selection and interpretability-focused machine learning project for customer churn prediction.  
> ✨ Integrated model insights from SHAP, PFI, RF importance, FK-RFE, and conditional PFI.

---

## 📌 Overview

This project aims to build an explainable, accurate machine learning pipeline for predicting customer churn in the telecom industry. Instead of relying on a single feature selection method, we combine multiple approaches—ensuring robust and interpretable feature importance.

---

## 🧠 Core Concepts

- 🔍 **Ensemble Feature Importance**: Combine SHAP, PFI, and RF's internal Gini-based feature importance to avoid single-model bias.
- 🌀 **FK-RFE**: A hybrid feature selection pipeline combining Kolmogorov filter and recursive elimination via Random Forest.
- 🌿 **Conditional PFI**: Improve traditional PFI by conditioning on local subgroups derived from decision tree paths (implemented with RF).
- ⚙️ **Model Benchmarking**: Random Forest, XGBoost, LightGBM, TabNet – compared for performance and interpretability.

---

## 🏗️ Project Structure

💡 Key Techniques Used

Permutation Feature Importance (PFI)
SHAP (Shapley Additive Explanations)
Random Forest Gini Importance
FK-RFE (Kolmogorov Filter + RF-RFE)
Conditional Permutation Feature Importance (cPFI)
TabNet Deep Feature Learning

📚 References

Fisher, A., Rudin, C., & Dominici, F. (2019). All models are wrong, but many are useful: Learning a variable's importance by studying an entire class of prediction models simultaneously. Journal of Machine Learning Research, 20(177), 1–81.
Lundberg, S. M., & Lee, S.-I. (2017). A unified approach to interpreting model predictions. Advances in Neural Information Processing Systems, 30.
Arik, S. Ö., & Pfister, T. (2021). TabNet: Attentive interpretable tabular learning. Proceedings of the AAAI Conference on Artificial Intelligence, 35(8), 6679–6687.
Zhang, Y., Zhu, Z., Liu, X., & Yang, W. (2023). A Model‐Free Feature Selection Technique of Feature Screening and Random Forest‐Based Recursive Feature Elimination. Expert Systems, 40(2), e13034.
Pfisterer, F., & Biecek, P. (2024). Model-agnostic feature importance and effects with dependent features: A conditional subgroup approach. Journal of Machine Learning Research, 25(25), 1–45.

🙌 Acknowledgements

Special thanks to National Chung Hsing University and the professors who guided this project.

📮 Contact

📧 [ccit0915@gmail.com]
🏫 Department of Information Management, National Chung Hsing University
