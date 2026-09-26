# 🤖 Machine Learning & Business Solutions Portfolio

> **End-to-end machine learning systems focused on real-world operations, dynamic pricing, and automated forecasting.**

Welcome! This repository contains practical, production-ready machine learning solutions built to solve actual business and supply chain problems—from automated pricing to demand forecasting and risk analysis.

---

## 🧰 Tech Stack & Tools

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; padding: 20px 0;">
  <a href="https://aws.amazon.com" target="_blank" title="Amazon Web Services"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v7/icons/amazonaws.svg" alt="AWS" width="55" height="55" /></a>
  <a href="https://www.python.org" target="_blank" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="55" height="55" /></a>
  <a href="https://www.docker.com/" target="_blank" title="Docker"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="55" height="55" /></a>
  <a href="https://scikit-learn.org/" target="_blank" title="Scikit-learn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" alt="Scikit-learn" width="55" height="55" /></a>
  <a href="https://pandas.pydata.org/" target="_blank" title="Pandas"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="55" height="55" /></a>
  <a href="https://numpy.org/" target="_blank" title="NumPy"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" width="55" height="55" /></a>
  <a href="https://git-scm.com/" target="_blank" title="Git"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="55" height="55" /></a>
</div>

* **Cloud & MLOps:** AWS (SageMaker, Serverless Inference, VPC), Docker, CI/CD.
* **Languages & Data:** Python, SQL, Pandas, NumPy, Scikit-Learn.
* **Core Models:** XGBoost, Random Forest, Prophet, K-Means, PCA.

---

## 🛠️ Project Standards (`00_ML_Project_Standards`)

Every project in this portfolio follows strict engineering rules to avoid common pitfalls:
* **No Data Leakage:** Strict train/test splits before scaling or transforming.
* **Clean Data Pipelines:** Automated handling of missing values and noise.
* **Model Validation:** Stratified cross-validation with proper error tracking.
* **Production Ready:** Exportable `.pkl` pipelines ready for deployment.

---

## 📈 Featured Projects & Impact

### 1. Enterprise Dynamic Pricing (`05_Enterprise_MLOps_Dynamic_Pricing_Infrastructure`)
* **The Problem:** Traditional systems react too late to sales data, leading to warehouse overstock and panic markdowns.
* **The Solution:** An AWS-native pricing pipeline that tracks user behavior and automatically adjusts pricing triggers.
* **Key KPIs & Results:** 
  * **~90% lower infrastructure costs** via serverless inference.
  * Real-time identification and automated liquidation of C-item (dead-stock) risks.

### 2. Predictive Catalog Onboarding (`04_Predictive_Classifier_New_Items_Ecommerce`)
* **The Problem:** Over half of newly added catalog items fail and become dead stock.
* **The Solution:** A supervised classification model (XGBoost/Random Forest) that scores new items using pre-purchase features before the first order is placed.
* **Key KPIs & Results:** 
  * **+150% increase** in A-item "Hit Rate" precision.
  * **-45% reduction** in dead-stock onboarding.

### 3. Strategic Vendor Intelligence (`03_Strategic_Vendor_Intelligence_PCA`)
* **The Problem:** Standard ABC analysis is too basic and misses hidden supply chain risks.
* **The Solution:** An unsupervised clustering model (PCA + K-Means) to group vendors based on reliability, revenue density, and portfolio health.
* **Key KPIs & Results:** 
  * **15% reduction** in total purchasing costs through strategic vendor consolidation.
  * **25% reduction** in catalog bloat, freeing up vital working capital.

### 4. Hybrid E-Commerce Sales Forecast (`02_Hybrid_ML_Sales_Forecast`)
* **The Problem:** Standard forecasting misses tactical spikes, causing inefficient warehouse staffing.
* **The Solution:** A hybrid approach combining Prophet (for seasonal trends) with XGBoost (for residual corrections).
* **Key KPIs & Results:** 
  * **~12% improvement** in warehouse labor efficiency through precise, demand-aligned staffing.

---

## 📂 Repository Structure

* `05_Enterprise_MLOps_Dynamic_Pricing_Infrastructure/`
* `04_Predictive_Classifier_New_Items_Ecommerce/`
* `03_Strategic_Vendor_Intelligence_PCA/`
* `02_Hybrid_ML_Sales_Forecast/`
* `01_Strategic-HR-Retention/`
* `00_ML_Project_Standards/`

---

## 📫 Connect

* **LinkedIn:** [sebastian-thurm-ai](https://www.linkedin.com/in/sebastian-thurm-ai)
* **YouTube:** [AI, MS & Data Decoded](https://www.youtube.com/@ai_ml_and_data_decoded)
