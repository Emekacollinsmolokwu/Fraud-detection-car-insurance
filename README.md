Fraud Detection in Car Insurance Claims Using Machine Learning and Data Analysis

Overview
This project presents a comprehensive machine learning framework for detecting fraudulent car insurance claims through advanced exploratory data analysis (EDA), statistical testing, feature engineering, SMOTE balancing, and ensemble modeling techniques. By addressing data imbalance, creating meaningful features, and optimizing predictive algorithms, the project achieved an accuracy of 84.5% and an AUC-ROC score of 0.841 with Random Forests, demonstrating strong real-world application potential for the insurance industry.

Problem Statement
Fraudulent car insurance claims cost the UK industry over £1.1 billion annually, leading to higher premiums and operational inefficiencies.
Traditional rule-based fraud detection systems are limited in adapting to complex and evolving fraud tactics.
This project leverages machine learning and advanced analytics to create a dynamic, scalable, and highly accurate fraud detection system.

Key Features
Comprehensive Data Analysis: Full EDA, missing value treatment, class distribution analysis.

Statistical Testing:
Chi-Square Test for categorical feature relevance.
ANOVA Test for numerical feature significance.
Correlation Analysis to uncover feature relationships.

Feature Engineering: Creation and transformation of key features to enhance model predictive power.

Class Balancing with SMOTE: Improved minority (fraud) class detection.

Machine Learning Modeling: Ensemble methods (Random Forest, AdaBoost, Gradient Boosting, XGBoost) and SVMs compared and evaluated.

Evaluation Metrics: Precision, Recall, F1-Score, AUC-ROC — providing a complete picture beyond simple accuracy.

Technologies Used
Python 3.11

Libraries: Pandas, NumPy, Scikit-Learn, Imbalanced-learn, Matplotlib, Seaborn, XGBoost

Environment: Jupyter Notebook

Dataset Overview
Publicly available synthetic car insurance dataset.

Target: Fraudulent vs Non-Fraudulent Claims.

Preprocessing: Missing value imputation, encoding categorical variables, feature scaling.

Data Analysis Techniques
Exploratory Data Analysis (EDA): Identification of missing values, variable distributions, fraud patterns.

Chi-Square Test: Found significant associations between categorical features and fraud.

ANOVA Test: Highlighted key differences in numerical variables like claim amounts.

Correlation Heatmap: Reduced redundancy among features.

Feature Engineering:

Combined and transformed related features.

Created ratio-based and time-based variables.

Model Performance Results

Model	Accuracy	Precision (Fraud 1)	Recall (Fraud 1)	F1-Score (Fraud 1)	AUC-ROC
Random Forest	84.5%	67.3%	71.4%	69.3%	0.841
AdaBoost	84.5%	63.6%	85.7%	73.0%	0.833
SVM	83.5%	62.5%	81.6%	70.8%	0.842
Gradient Boosting	81.5%	60.0%	73.5%	66.1%	0.827
k-Nearest Neighbors (k-NN)	80.0%	58.5%	63.3%	60.8%	0.788
Decision Tree	79.5%	58.7%	55.1%	56.8%	0.713
XGBoost	79.5%	57.7%	61.2%	59.4%	0.809
Naive Bayes	76.5%	55.0%	22.4%	31.9%	0.771
Logistic Regression	64.5%	29.6%	32.7%	31.1%	0.599
Key Insights
Random Forest achieved the highest combination of accuracy, F1-Score, and AUC-ROC.

AdaBoost delivered exceptional fraud recall (85.7%), critical for minimizing undetected fraud cases.

SVM provided strong balance between fraud detection precision and recall.

Application of SMOTE significantly enhanced detection capability of all models.

Logistic Regression performed poorly, confirming the need for advanced ensemble methods.

Project Structure
plaintext
Copy
Edit
/ 📂 data               # Processed and raw dataset
/ 📂 notebooks          # Jupyter notebooks: EDA, statistical testing, modeling
/ 📂 models             # Trained model files (pickle format)
/ 📂 reports            # Visualizations and evaluation metrics
/ README.md             # Project overview (this file)
/ requirements.txt      # Python package dependencies
Future Work
Advanced hyperparameter optimization (GridSearchCV, RandomSearchCV).

Real-time fraud detection deployment via Flask or FastAPI APIs.

Integration of deep learning techniques (e.g., Autoencoders for anomaly detection).

Utilization of NLP techniques on textual claims for more robust fraud detection.

Business Impact
Significant potential for cost reduction by improving early fraud detection.

Operational efficiency through automation of claim screening.

Restoration of customer trust by minimizing false positives.

Regulatory compliance through transparent and explainable ML models.

Contact
Molokwu Emeka Collins
Email: (Insert Your Professional Email)
GitHub: (Your GitHub Profile URL)
[LinkedIn Profile] (Optional — highly recommended if available)
