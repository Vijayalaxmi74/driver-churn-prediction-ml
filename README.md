# driver-churn-prediction-ml
End-to-end machine learning project to predict driver churn using feature engineering, ensemble models, SHAP explainability, and data-driven business insights.
-----------
* **Project Title**                       
Driver Churn Prediction using Machine Learning

* **Problem Statement**                        
Driver churn is a critical issue in ride-sharing platforms, impacting service availability and revenue. This project aims to identify drivers likely to churn and provide actionable insights to improve retention.

* **Approach**                      
Performed Exploratory Data Analysis (EDA) to understand churn patterns
Engineered key features such as:
Active months (engagement)
Income trends and stability
Rating changes
Business value variability
Built and compared models:
Random Forest
Gradient Boosting
XGBoost
Evaluated using:
ROC-AUC
Precision, Recall, F1-score
Confusion Matrix
Applied SHAP for model interpretability

* **Key Insights**                         
Churn is primarily driven by low engagement and poor performance
Behavioral features dominate over demographic features
Drivers with higher activity and stable earnings are less likely to churn

  * **Results**                            
Achieved ~0.86 ROC-AUC
Balanced performance with strong precision and recall
Successfully identified key churn drivers using SHAP

*  **Business Impact**                        
Enables early identification of at-risk drivers
Supports targeted retention strategies
Potential to reduce churn and improve revenue stability

* **Tech Stack**                                    
Python (Pandas, NumPy, Scikit-learn)
XGBoost
Matplotlib, Seaborn
SHAP

* **Key Challenge**                                 
Time-based data splitting initially resulted in no churn cases in the test set due to churn definition.
This was resolved using a stratified random split, ensuring reliable evaluation.

* **Project Highlights**                    
End-to-end ML pipeline from EDA to business recommendations
Advanced feature engineering capturing driver behavior
Model explainability using SHAP
Strong alignment between data insights and business decisions
