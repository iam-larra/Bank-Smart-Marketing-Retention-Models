# 📌 Predictive Modeling to Enhance Customer Retention through Targeted Marketing

## 📖 Overview  
This project explores how machine learning and deep learning models can be applied to predict customer behaviour and enhance retention through personalized marketing strategies in the banking sector.

## 🎯 Objectives  
- Forecast customer responses to marketing campaigns  
- Compare various predictive models to identify the most effective approach  
- Derive insights to support data-driven decision-making in customer retention
## 📁 Dataset
- **Source:** UCI Bank Marketing Dataset
- **Target Variable:** Customer subscription to term deposits (used as retention indicator)
- **Features:** Customer demographics, financial attributes, campaign details, and temporal factors

## 🧠 Algorithms Used
- Random Forest    (85.58%, AUC: 0.92) ⭐
- XGBoost         (85.45%, AUC: 0.92) ⭐
- Decision Tree   (85.58%, AUC: 0.85)
- Deep Neural Net (84.82%)
- MLP            (82.62%)
- Logistic Reg   (82.27%)

## 🔑 Key Findings
**Critical Success Factors**

- **Duration of contact** is the #1 predictor across all models
- **Customer balance** strongly influences retention likelihood
- **Previous campaign success** is a powerful predictor
- **Seasonal timing** (especially May) affects response rates

**Business Insights**

- Longer customer interactions → Higher retention probability
- High-balance customers are prime retention targets
- Past positive interactions predict future success
- Campaign timing optimization can boost effectiveness
  
## 🧰 Tools & Libraries  
- Python (Pandas, NumPy, Scikit-learn, TensorFlow/Keras)  
- Jupyter Notebook  
- Matplotlib & Seaborn (for visualization)  

## 🔍 Key Features of the Workflow  
- Data Preprocessing & Feature Engineering  
- Exploratory Data Analysis (EDA)  
- Model Training and Evaluation
- Hyperparameter tuning 
- Comparison of performance using accuracy, AUC, precision, and recall  
- Visualization of performance metrics

## 📊 Results Summary  
- **Random Forest** and **XGBoost** delivered the highest AUC scores (0.92) and strong overall accuracy (85%+)  
- **Decision Tree** offered strong interpretability with good performance  
- **Deep Learning models** showed promise but were impacted by overfitting

## 📈 Business Impact

- **85%+ prediction accuracy** for customer retention
- **Data-driven marketing** strategy optimization
- **Resource allocationP** improvement through targeted campaigns
- **ROI enhancement** via personalized customer engagement

## 💡Key Recommendations

- **Extend customer interaction duration** for better retention
- **Target high-balance customers** with premium strategies
- **Leverage seasonal patterns** for campaign timing
- **Use Random Forest/XGBoost** for production deployment
- **Build on previous campaign successes**

## 🛠️ How to Run  
```bash
# Clone this repo
git clone https://github.com/iam-larra/Bank-Smart-Marketing-Retention-Models.git

# Open the notebook
jupyter notebook Customer Retention.ipynb
