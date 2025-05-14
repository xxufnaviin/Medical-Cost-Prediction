# Medical Cost Prediction
This project aims to analyze the factors influencing healthcare costs and predict individual medical expenses using regression models. It leverages machine learning techniques such as **hyperparameter tuning**, **cross-validation**, and **model evaluation** to improve predictive performance.

✅ The optimized Decision Tree Regressor performed strongly, achieving an R² score of ~0.83 during cross-validation and test evaluation, indicating the model effectively explains the majority of the variance in medical charges. 📈💡
###
## 🔍 Key Findings & Insights
#### 1️⃣ Smoking status is the most significant driver of higher medical costs.
#### 2️⃣ Individuals with a higher BMI (above 30) are associated with increased healthcare charges.
#### 3️⃣ Age has a positive correlation with medical expenses — older individuals tend to have higher costs.
#### 4️⃣ The number of dependent children has a modest effect on cost, with more children generally linked to higher charges.
#### 5️⃣ Gender and region have minimal impact on charges, indicating limited predictive power.

## 📂Dataset

The medical cost dataset is used to evaluate the effectiveness of regression models in predicting individual healthcare expenses based on personal and lifestyle attributes. By analyzing factors such as age, BMI, smoking status, number of children, and region, this dataset helps assess model accuracy and identify key drivers of medical charges.

**Source**: Medical Cost Dataset
https://www.kaggle.com/datasets/mirichoi0218/insurance/data

###
## 💡Methods
- Programming Language: Python
- Data Manipulation: Pandas, Numpy
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, Hyperparameter Tuning, Cross Validation
- Development Environment: Jupyter Notebook

###
## ⚙️Instructions

#### Steps:
##### 1. Open Git CMD/ Git Bash
##### 2. Clone the repository  
```bash
git clone https://github.com/xxufnaviin/Medical-Cost-Prediction
```
##### 3. Navigate to project directory 
```bash
cd Medical-Cost-Prediction
```
##### 4. Install Dependencies
```bash
pip install -r requirements.txt
``` 
##### 5. Open the jupyter notebook 
```bash
jupyter notebook MedicalCost.ipynb
```
