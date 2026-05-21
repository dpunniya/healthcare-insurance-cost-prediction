# 🏥 Healthcare Insurance Cost Prediction

A machine learning pipeline that predicts healthcare insurance costs using Gradient Boosting, uncovering how smoking status, age, and BMI interact to drive costs.

## 📌 What It Does
- Performs exploratory data analysis on 1,338 insurance records
- Engineers interaction features (smoking × age, smoking × BMI) to capture cost drivers
- Trains and compares 5 ML models: Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting
- Evaluates models using MAE, RMSE, and R² metrics
- Identifies smoking status, age, and BMI as primary cost predictors

## 📊 Key Findings
- Smokers pay significantly higher insurance costs across all age groups
- BMI interacts with smoking status to amplify costs
- Gradient Boosting outperforms linear models by capturing non-linear feature interactions

## 🛠️ Tech Stack
- **Python** — core implementation
- **Scikit-learn** — ML models and evaluation
- **Pandas, NumPy** — data processing and feature engineering
- **Matplotlib, Seaborn** — EDA visualizations
- **Google Colab** — development environment

## 📁 Project Structure
├── TeamAI_HealthcareModel.ipynb  # Full ML pipeline notebook
└── insurance.csv                  # Dataset (1,338 records)
## 🔍 Dataset Features
| Feature | Description |
|---------|-------------|
| age | Patient age |
| bmi | Body mass index |
| smoker | Smoking status (yes/no) |
| children | Number of dependents |
| region | US geographic region |
| charges | Insurance cost (target) |

## 👩‍💻 Author
**Dharani Punniyamoorthi** — NEXIS Technology Lab, Team AI
- LinkedIn: [linkedin.com/in/dharanipunniyamoorthi](https://linkedin.com/in/dharanipunniyamoorthi)
- Email: dharanimoorthi2002@gmail.com
