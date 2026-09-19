# Machine Learning Portfolio

Applied machine learning projects covering supervised learning, deep learning, computer vision, NLP and production deployment. Completed as part of the **Post Graduate Program in Artificial Intelligence and Machine Learning: Business Applications** — McCombs School of Business, The University of Texas at Austin.

Each notebook is a self-contained study: business problem, exploratory analysis, preprocessing, model building, tuning, evaluation and recommendations.

---

## Projects

### [05 — SuperKart: Sales Forecasting with Production Deployment](notebooks/05-superkart-forecasting-deployment.html)
End-to-end regression project taken all the way to a live service.

- Random Forest and XGBoost regressors, tuned and compared on test RMSE
- Model serialised with `joblib`
- Containerised **Flask** prediction API with single and batch endpoints
- Separate **Streamlit** frontend, both deployed as Docker Spaces

**Stack:** scikit-learn · XGBoost · Flask · Docker · Streamlit · Hugging Face Spaces

---

### [06 — HelmNet: Safety Helmet Detection](notebooks/06-helmnet-helmet-detection.html)
Binary image classification for workplace safety compliance monitoring.

- Dataset of 631 images across two classes, near-balanced
- Four architectures compared: custom CNN, VGG-16 base, VGG-16 + FFNN, VGG-16 + FFNN + augmentation
- Final model achieved **100% accuracy, precision, recall and F1** on the held-out test set
- Deployment recommendations for real-time CCTV monitoring

**Stack:** TensorFlow · Keras · CNNs · VGG-16 transfer learning

---

### [04 — Clinical RAG Assistant](notebooks/04-clinical-rag-assistant.html)
Retrieval-augmented generation pipeline for grounded clinical question answering.

- Corpus built from curated summaries and extracted medical reference text
- TF-IDF retriever with configurable retrieval depth (`k`)
- Baseline vs prompt-engineered vs RAG answers compared
- Evaluation harness measuring **groundedness** and **relevance** against expected clinical terminology

**Stack:** Python · NLP · TF-IDF retrieval · prompt engineering · LLM integration

---

### [07 — ReneWind: Predictive Maintenance for Wind Turbines](notebooks/07-renewind-predictive-maintenance.html)
Failure prediction on ciphered sensor data from wind turbine generators.

- 25,000 observations across 40 predictors, heavily imbalanced target
- Seven neural network configurations compared (optimisers, depth, dropout, class weighting)
- Class weighting and dropout tuned to maximise F1 on the minority failure class
- Median imputation and feature scaling pipeline

**Stack:** TensorFlow · neural networks · imbalanced classification

---

### [02 — EasyVisa: Visa Certification Prediction](notebooks/02-easyvisa-certification-prediction.html)
Classification model to support shortlisting of labour certification applications.

- Full EDA across education, experience, region and prevailing wage
- Original, oversampled and undersampled training compared
- Bagging and boosting ensembles with hyperparameter tuning
- Feature importance analysis driving business recommendations

**Stack:** scikit-learn · ensemble methods · SMOTE · hyperparameter tuning

---

### [01 — AllLife Bank: Loan Propensity](notebooks/01-alllife-bank-loan-propensity.html)
Predicting which deposit customers will convert to personal loan customers.

- Decision tree classifier with pre-pruning and post-pruning compared
- Model selection on ROC AUC
- Decision rules extracted and feature importance ranked
- Segmentation recommendations for campaign targeting

**Stack:** scikit-learn · decision trees · cost-complexity pruning

---

### [03 — FoodHub: Exploratory Data Analysis](notebooks/03-foodhub-exploratory-analysis.html)
Order and delivery analysis for a food aggregator platform.

- Univariate and multivariate analysis across order, restaurant and delivery variables
- Revenue modelling under a tiered commission structure
- Weekday vs weekend delivery time comparison
- Promotional eligibility analysis by rating threshold

**Stack:** pandas · NumPy · Matplotlib · Seaborn

---

## Viewing the notebooks

The notebooks are stored as rendered HTML with all outputs, plots and results intact — no environment setup needed. Download a file and open it in any browser, or view it through [nbviewer](https://nbviewer.org/).

---

## Author

**Kerolous Samir Fekry** — AI Engineer & System Administrator

[LinkedIn](https://www.linkedin.com/in/kerolous-samir-ai) · [Virtspire](https://virtspire.com)
