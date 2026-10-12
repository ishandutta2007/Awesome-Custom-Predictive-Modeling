# Awesome-Custom-Predictive-Modeling

# Top Custom Predictive Modeling Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AutoML, Feature Engineering & Production Model Deployment*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Custom Predictive Modeling**. These tools enable organizations to build, train, and deploy machine learning models without extensive data science expertise — automating feature engineering, model selection, hyperparameter tuning, and production deployment for business forecasting, lead scoring, churn prediction, and demand planning.

**Examples** include Salesforce Einstein Prediction Builder, DataRobot, Pecan AI, Akkio, Dataiku, Obviously AI, BigML, dotData, H2O.ai, and KNIME (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom feature engineering, and open AutoML pipelines — ideal for data scientists, analysts, and developers seeking transparent, vendor-independent predictive modeling.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Einstein Prediction Builder](https://help.salesforce.com/)**  
  No-code custom AI for Salesforce admins. Point-and-click prediction building on standard and custom objects (Account, Opportunity, Lead, Case, etc.). Requires minimum 400 records for training. Supports Checkbox, Formula, and Numeric (Beta) field types. Predictions surface as scores on records and can be used in workflows .

- **[DataRobot](https://www.datarobot.com/)**  
  Enterprise AI platform providing a unified experience for developing, delivering, and governing predictive and generative AI. Workbench for experimentation, Registry for model versioning, and Console for deployment monitoring. Supports one-click deployments to serverless or dedicated prediction servers .

- **[Pecan AI](https://www.pecan.ai/)**  
  Predictive AI agent built for business outcomes. Automates data prep and modeling, delivering predictions directly to CRM. Use cases include churn prediction, lead scoring, LTV modeling, demand forecasting, and fraud prevention. Claims 90% of predictions delivered without data science support .

- **[Akkio](https://www.akkio.com/)**  
  Predictive analytics and modeling platform empowered by generative AI. Founded 2019, headquartered in Cambridge, MA. Serves businesses of all sizes with swift insights and predictive capabilities for operational efficiency .

- **[Dataiku](https://www.dataiku.com/)**  
  Enterprise AI platform uniting people, orchestration, and governance. No-code, low-code, and full-code interfaces for analytics, ML, and AI agents. Works across any cloud or infrastructure without vendor lock-in. $350M ARR, 750+ customers, 1,200+ employees globally .

- **[Obviously AI](https://obviously.ai/)**  
  B2B predictive analytics startup based in San Francisco. Enables non-technical business analysts to run predictions on historical data with just a few clicks. Mission to turn every company into an AI company. Backed by TMV, UTEC, B Capital, and others .

- **[BigML](https://bigml.com/)**  
  Cloud-based machine learning platform founded 2011, headquartered in Corvallis, USA. Provides scalable ML services for data-driven decision making. Accessible to non-experts — upload data and start exploring. Use cases include customer behavior, risk profiles, and stock management .

- **[dotData](https://www.dotdata.com/)**  
  Leader in automated feature discovery and extraction platform. dotData Enterprise 4.0 features AI-powered automated feature engineering that analyzes complex relational data in hours, extracting transparent and explainable features without human bias. Trusted by Fortune 500 companies .

- **[H2O.ai](https://h2o.ai/)**  
  Open-source and enterprise AI platform. H2O Python module provides scalable machine learning with H2OFrame for big data operations, GLM, Gradient Boosting, Deep Learning, and AutoML. Models inherit from H2OEstimator with scikit-learn-style train/predict interfaces .

- **[KNIME](https://www.knime.com/)**  
  Open-source platform for visual workflows enabling data manipulation, analysis, and machine learning. KNIME Analytics Platform is free desktop software; KNIME Pro (€19/month) adds cloud automation, scheduling, and interactive data apps. K-AI assists with repetitive tasks .

## Open-Source GitHub Projects

- **[H2O-3](https://github.com/h2oai/h2o-3)**  
  Open-source, distributed, scalable machine learning platform (Apache-2.0). Features AutoML, GLM, Gradient Boosting, Random Forest, Deep Learning, and Stacked Ensembles. Python, R, and REST APIs. Handles billions of rows on commodity hardware. 7k+ GitHub stars.

- **[AutoGluon](https://github.com/autogluon/autogluon)**  
  AutoML toolkit (Apache-2.0) by AWS for tabular, image, text, and time series data. Features multi-layer stacking, automatic feature engineering, and hyperparameter tuning. Top performer on Kaggle competitions. 9k+ GitHub stars.

- **[PyCaret](https://github.com/pycaret/pycaret)**  
  Low-code machine learning library (MIT) that automates ML workflows. Features data preprocessing, feature engineering, model training, hyperparameter tuning, and deployment — all in a few lines of code. 9k+ GitHub stars.

- **[Auto-sklearn](https://github.com/automl/auto-sklearn)**  
  Automated machine learning toolkit (BSD-3-Clause) built on scikit-learn. Features automated algorithm selection, hyperparameter tuning, and ensemble construction. 7k+ GitHub stars.

- **[TPOT](https://github.com/EpistasisLab/tpot)**  
  Automated machine learning tool (LGPL-3.0) that optimizes ML pipelines using genetic programming. Features feature preprocessing, model selection, and hyperparameter optimization. 9k+ GitHub stars.

- **[Featuretools](https://github.com/alteryx/featuretools)**  
  Automated feature engineering library (BSD-3-Clause) for relational and transactional data. Features deep feature synthesis, primitives, and customizable feature generation. 7k+ GitHub stars.

- **[Raikura](https://pypi.org/project/raikura/)**  
  Advanced modular Python ML library extending beyond scikit-learn. Integrates classical ML, deep learning, transformers, time series forecasting, fairness auditing, AutoML pipelines, and model interpretability (SHAP, LIME, Captum). YAML-configured pipelines with CLI and REST API interfaces .

- **[features-goldmine](https://pypi.org/project/features-goldmine/)**  
  Automated feature engineering package that generates candidate features using LightGBM tree paths, numeric transformations, and context features. Features a competition-based selection process where candidates compete against raw features. Win rate of 52.9% across 51 datasets .

- **[FELITS](https://pypi.org/project/felits/)**  
  Open-source Python library for end-to-end time series analysis and forecasting. Features outlier detection, STL decomposition, cyclic encodings, lag features, FFT, wavelets, Granger causality, KSG mutual information, XGBoost, RandomForest, LSTM/GRU, and SHAP/LIME explainability. Optuna hyperparameter optimization .

- **[ClearML Serving](https://pypi.org/project/clearml-serving/)**  
  Open-source model serving infrastructure (Apache-2.0) for deploying ML models as REST APIs. Supports scikit-learn, XGBoost, TensorFlow, PyTorch, and custom models. Features auto-deployment, canary endpoints, and CI/CD integration .

- **[FairLabeler](https://github.com/fairlabeler/anonymous)**  
  Model-agnostic preprocessing approach (IEEE Intelligent Systems 2026) that detects and massages biased labels in training datasets. Improves individual- and group-level fairness while preserving predictive performance. Evaluated on 9 real-world datasets .

### Additional Strong Open-Source Options

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)** — Foundational ML library (BSD-3-Clause) with classification, regression, clustering, and preprocessing.
- **[XGBoost](https://github.com/dmlc/xgboost)** — Optimized gradient boosting (Apache-2.0) for tabular prediction tasks.
- **[LightGBM](https://github.com/microsoft/LightGBM)** — Fast gradient boosting framework (MIT) by Microsoft.
- **[CatBoost](https://github.com/catboost/catboost)** — Gradient boosting with categorical feature support (Apache-2.0).
- **[MLflow](https://github.com/mlflow/mlflow)** — ML lifecycle platform (Apache-2.0) for experiment tracking, model registry, and deployment.
- **[Optuna](https://github.com/optuna/optuna)** — Hyperparameter optimization framework (MIT) with pruning and distributed tuning.
- **[SHAP](https://github.com/shap/shap)** — Model interpretability library (MIT) for explaining predictions.
- **[LIME](https://github.com/marcotcr/lime)** — Local interpretable model-agnostic explanations (BSD-2-Clause).

**Frameworks for building custom systems**: Combine **H2O-3** or **AutoGluon** as the AutoML engine with **Featuretools** or **features-goldmine** for automated feature engineering, **MLflow** for experiment tracking and model registry, **ClearML Serving** for production deployment, and **SHAP** for explainability — creating a fully self-hosted, enterprise-grade predictive modeling platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Predictive models trained on personal data must comply with data protection regulations (GDPR, CCPA, etc.) and fairness/bias auditing requirements.
- Self-hosted open-source solutions require proper security hardening, model monitoring, and ongoing maintenance for production reliability.

---

**Made for data scientists, analysts, business intelligence teams, and developers building transparent predictive modeling solutions.**  
Let's make custom predictive modeling more open, data-driven, and accessible.
