# 🧠 Mental Health in Tech🖥️

This project analyzes a survey dataset related to mental health in the tech industry. The goal is to build a predictive model that can classify whether an individual has sought treatment for mental health issues based on survey responses.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📋 Project Overview

This project explores the **Mental Health in Tech Survey** dataset to analyze patterns, perform Exploratory Data Analysis (EDA), and build machine learning models that predict whether a person working in the tech industry seeks mental health treatment.

The analysis focuses on understanding how workplace culture, employer support, and personal factors affect mental health. Multiple machine learning models were trained and evaluated to identify the best-performing classifier.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Objectives

- Explore and understand the **mental health landscape** in the tech industry.  
- Perform **data preprocessing** and cleaning to ensure data quality.  
- Conduct **Exploratory Data Analysis (EDA)** to uncover insights and correlations.  
- Train multiple machine learning models for prediction.  
- Evaluate and compare model performance using **accuracy** and **AUC-ROC Curve**.  
- Save the best-performing model for future use.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features

- Import and organize essential libraries.  
- Load and inspect dataset structure.  
- Handle missing values and encode categorical variables.  
- Perform **EDA** using visualizations (heatmaps, bar charts, correlation plots).  
- Train and evaluate:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
  - LightGBM  
- Compare models using accuracy and AUC-ROC curve.  
- Save the trained model using joblib/pickle.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧰 Tools and Technologies

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming Language** | Python |
| **Data Analysis & Visualization** | Pandas, NumPy, Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn, XGBoost, LightGBM |
| **Model Evaluation** | Accuracy Score, ROC-AUC Curve, Confusion Matrix |
| **Environment** | Kaggle Notebook |

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Dataset
- **Name:** Mental Health in Tech Survey  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)  
- **Description:**  
  This dataset contains survey responses from people working in the tech industry, focusing on attitudes toward mental health, workplace support, and treatment-seeking behavior.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Results

| Model | Accuracy | Remarks |
|--------|-----------|----------|
| **Random Forest** | **71%** | Best overall performance |
| Logistic Regression | 67% | Good baseline |
| XGBoost | 69% | Competitive accuracy |
| LightGBM | 69% | Similar to XGBoost |

**EDA:**

<img width="567" height="428" alt="image" src="https://github.com/user-attachments/assets/ab0b9e4f-477e-42f0-8cc7-58dc53fe2ba0" />

<img width="844" height="538" alt="image" src="https://github.com/user-attachments/assets/0989f513-bcb2-4f1b-a837-9f7d926a6c6a" />

<img width="826" height="463" alt="image" src="https://github.com/user-attachments/assets/bdf2b793-fddd-439f-8cc2-6086325d85eb" />

<img width="535" height="384" alt="image" src="https://github.com/user-attachments/assets/e1b53064-3e0c-48c2-bfd2-de0f3f17f264" />


**Best Model:** Random Forest  
**Evaluation Metric:** Accuracy & AUC-ROC Curve

**Classification Report:**

- Random Forest:
  
<img width="576" height="229" alt="image" src="https://github.com/user-attachments/assets/ff3c8fc8-db38-4f07-9c3c-a1e53a74f596" />

- Logistic Regression:

<img width="509" height="202" alt="image" src="https://github.com/user-attachments/assets/4994a446-ecd6-41ee-95c9-11f2f33069e1" />

- XG Boost:

<img width="475" height="204" alt="image" src="https://github.com/user-attachments/assets/c956309a-967d-4df4-905d-ba1af36b93f5" />

- LightGBM:

<img width="499" height="203" alt="image" src="https://github.com/user-attachments/assets/151d3af2-a12e-43aa-a466-bfb8cc9d0746" />

- AUC-ROC Curve:

<img width="787" height="548" alt="image" src="https://github.com/user-attachments/assets/70452974-61da-452f-a8c9-2f18d5be0c1c" />



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔍 References

1. **Kaggle Notebook:**  
   [Mental Health in Tech — EDA & ML Models](https://www.kaggle.com/code/muqaddasejaz/mental-health-in-tech-eda)

2. **Dataset Source:**  
   [OSMI Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)

3. **Official Documentation:**  
   - [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)  
   - [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)  
   - [LightGBM Documentation](https://lightgbm.readthedocs.io/en/latest/)  
   - [Pandas Documentation](https://pandas.pydata.org/docs/)  
   - [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)  
   - [Seaborn Documentation](https://seaborn.pydata.org/)

4. **Additional Reading:**  
   - [Understanding AUC-ROC Curve — Towards Data Science](https://towardsdatascience.com/understanding-auc-roc-curve-68b2303cc9c5)  
   - [Ensemble Learning Methods — Scikit-learn User Guide](https://scikit-learn.org/stable/modules/ensemble.html)


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

AI/ML Engineer

Data Science & Gen AI Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

📬 Kaggle: [Kaggle Profile](https://www.kaggle.com/muqaddasejaz) 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
