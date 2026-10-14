<h1 align="center">Hi 👋, I'm Shadab Ansari</h1>
<h3 align="center">M.Tech (Computer Science & IT) @ MANUU, Hyderabad | Machine Learning · Explainable AI · MLOps</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/shadab-ansari-dln/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://shadabdln.medium.com/"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="mailto:shadabahamed63@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://x.com/ShadabChirps"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
</p>

---

## 🧑‍💻 About me

I build **explainable, reproducible machine learning systems**, from raw data to a deployed app. My M.Tech research applies ML to cancer survival prediction on large clinical registry data.

- 🔬 **Current research:** explainable ML for 5-year colorectal cancer survival on **257,827** SEER patients, with external validation on AACR Project GENIE
- 🛠️ **I work with:** Python, scikit-learn, XGBoost, LightGBM, SHAP, survival analysis, MLflow, DVC, Docker
- 🌱 **Currently learning:** deep learning and neural networks
- 💬 **Ask me about:** machine learning, model explainability (SHAP), MLOps, Python for data science
- 📫 **Reach me:** [shadabahamed63@gmail.com](mailto:shadabahamed63@gmail.com)
- ⚡ **Fun fact:** coffee enthusiast ☕, nature lover 🌳, and music keeps me focused 🎵

---

## 🚀 Featured project

### [Explainable ML for 5-Year Colorectal Cancer Survival Prediction](https://github.com/shadabdln/crc-seer-survival)

An end-to-end, reproducible ML pipeline that predicts five-year overall survival for colorectal cancer patients and explains each prediction.

| What | Result |
|---|---|
| Cohort | 257,827 patients, SEER 17 registries |
| Final model (Gradient Boosting) | ROC-AUC **0.877** (95% CI 0.874–0.880) on 50,338 held-out patients |
| Temporal validation (train 2010–2015, test 2016–2018) | ROC-AUC **0.878** |
| External validation (AACR Project GENIE BPC CRC) | ROC-AUC **0.790** |
| Survival models (Cox, CoxNet, RSF, GB Survival, XGBoost-Cox) | best C-index **0.809** |

**Highlights**
- Benchmarked 6 classifiers (Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost, LightGBM) with stratified 5-fold CV and bootstrap confidence intervals
- Explainability with **SHAP**, LIME and partial dependence plots
- **MLOps:** DVC pipeline (prepare → train → evaluate), MLflow tracking and Model Registry on DagsHub, pytest, GitHub Actions CI
- **Deployment:** Flask web app with a calibrated survival probability and top SHAP factors, packaged with Docker and Kubernetes manifests

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> 📄 A paper on this work (S. Ansari, M. Omar) is prepared for submission to ICCIDSDT-2027 (Springer LNNS).

---

## 🧰 Tech stack

**Languages & data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Machine learning & explainable AI**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![Optuna](https://img.shields.io/badge/Optuna-2C5BB4?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=for-the-badge)
![LIME](https://img.shields.io/badge/LIME-32CD32?style=for-the-badge)
![lifelines](https://img.shields.io/badge/lifelines-4B8BBE?style=for-the-badge)
![scikit--survival](https://img.shields.io/badge/scikit--survival-306998?style=for-the-badge)

**Visualization**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

**MLOps & deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white)
![DagsHub](https://img.shields.io/badge/DagsHub-F05032?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Web & tools**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge)

---

## 📂 Other projects

| Project | Stack |
|---|---|
| [Blog Management](https://github.com/shadabdln/CodeClauseInternship_Blog_Management) (CodeClause internship) | JavaScript |
| [To-do App](https://github.com/shadabdln/CodeClauseInternship_Todo-app) (CodeClause internship) | HTML, CSS |
| [Online Resume](https://github.com/shadabdln/CodeClauseInternship_Basic__online_Resume) (CodeClause internship) | HTML |
| [OIBSIP](https://github.com/shadabdln/OIBSIP) (internship tasks) | HTML, CSS |
| Google Drive Clone (Dev Town, Microsoft Learn & GDSC KIIT bootcamp) | HTML5, CSS3 |

---

## 🏆 Achievements

- 🥉 3rd Rank, Coding Ninjas Coding Byte Contest
- 🎓 MCA, MANUU, CGPA 8.4/10
- 🎭 Coordinator of Cultural Activities, MANUU

---

<p align="center">⭐ If you find my work interesting, feel free to star the repo or connect with me on <a href="https://www.linkedin.com/in/shadab-ansari-dln/">LinkedIn</a>.</p>
