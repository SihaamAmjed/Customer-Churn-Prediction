# Customer-Churn-Prediction
The objective of this platform is to predict, analyze, and prevent customer churn using machine learning
 
## End-to-End Machine Learning Pipeline with Streamlit Deployment

---

##  Project Overview

Customer churn is a critical challenge for subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project builds a complete **end-to-end Machine Learning system** that predicts whether a customer is likely to churn and provides an interactive dashboard for real-time business insights.

The solution covers the full ML lifecycle:

- Data preprocessing  
- Feature engineering  
- Model training & evaluation  
- Model persistence  
- Deployment using Streamlit  
- Single & bulk prediction functionality  

---

##  Problem Statement

To design and deploy a predictive machine learning system that identifies customers at high risk of churn, enabling proactive retention strategies and reducing revenue loss.

---

##  Tech Stack

### Programming & Machine Learning
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  

### Visualization
- Matplotlib  
- Seaborn  

### Deployment
- Streamlit  
- Joblib  

---

##  Machine Learning Workflow

###  Data Cleaning
- Handling missing values  
- Data type corrections  

###  Feature Engineering
- Encoding categorical variables  
- Feature scaling  
- Creating derived features  

###  Train-Test Split
- Stratified splitting for balanced evaluation  

###  Model Training
- XGBoost Classifier  

###  Model Evaluation
- Accuracy Score  
- ROC-AUC Score  
- Confusion Matrix  
- Feature Importance Analysis  

###  Model Saving
- Serialized using Joblib  

###  Deployment
- Interactive dashboard using Streamlit  
- Real-time prediction interface  

---

##  Model Performance

-  Accuracy: **XX%**  
-  ROC-AUC Score: **XX%**  
-  Confusion Matrix Analysis  
-  Feature Importance Insights  

> Replace XX% with your actual performance metrics.

---

##  Live Demo

 https://churn-dashboard-mzkrzm4xlvjnh29jq9pjja.streamlit.app/

---

##  Project Structure


churn-dashboard/
│
├── pages/ # Streamlit multipage components
├── app.py # Main dashboard application
├── batch_predict.py # Bulk CSV prediction script
├── churn_model.pkl # Trained XGBoost model
├── train_sample.csv # Training dataset sample
├── bulk_demo.csv # Sample bulk prediction dataset
├── requirements.txt # Dependencies
└── README.md


---

##  Key Features

-  Single Customer Prediction  
-  Bulk CSV Upload & Batch Prediction  
-  Interactive Data Visualization  
-  Feature Importance Dashboard  
-  Churn Risk Scoring  
-  Clean & Professional UI  

---

##  Business Impact

This system enables organizations to:

- Identify high-risk customers early  
- Design targeted retention campaigns  
- Reduce customer attrition  
- Improve revenue stability  
- Make data-driven strategic decisions  

---

##  Future Improvements

- SHAP Explainability Integration  
- REST API Deployment (FastAPI)  
- User Authentication System  
- Cloud Deployment (AWS / Azure)  
- Real-time Database Integration  
- Model Monitoring & Drift Detection  

---

##  Author

**Sihaam**  
Machine Learning & AI Enthusiast  

---

⭐ If you find this project useful, consider giving it a star!
