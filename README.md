📞 Telecom Customer Churn Prediction

🧠 Project Overview

Customer churn is a key metric in the telecom industry. This project focuses on predicting whether a customer will leave (churn) using historical telecom customer data. The goal is to enable proactive customer retention strategies through machine learning models.


---

📁 Contents

Project Overview

Dataset

Project Structure

Installation

How to Use

Models Used

Results

Conclusion

References



---

📊 Dataset

Source: [e.g., Kaggle, IBM Sample Dataset, or custom]

Records: ~7,000 customer records

Features:

Demographics (gender, senior citizen, partner, etc.)

Account info (tenure, contract type, payment method, etc.)

Service usage (internet service, streaming, etc.)

Target: Churn (Yes/No)




---

🧱 Project Structure

telecom-churn/
│
├── .ipynb notebooks/  # Jupyter notebooks for EDA & modeling & Training
├── _templates_/       # Model metrics and plots
├── README.md          # Project overview
└── requirements.txt   # Required packages


---

⚙ Installation

1. Clone the repository:



git clone https://github.com/REHANAHEMAD17/Telecom_Customer_Churn_Prediction.git

cd Telecom_Customer_Churn_Prediction

2. Create a virtual environment (optional but recommended):


3. Install dependencies:



pip install -r requirements.txt


---

▶ How to Use

Run the main training script:

python src/train_model.py

For exploratory data analysis:

jupyter notebook notebooks/EDA.ipynb

To make predictions:

python src/predict.py --input data/sample_input.csv


---

🤖 Models Used

Logistic Regression

Decision Tree

Random Forest

AdaBoost

KNN

Support Vector Machine

Neural Networks (optional)



---

📈 Results

Model	Accuracy	Precision	Recall	F1 Score	ROC-AUC

Logistic Regression	80.0%	75.0%	78.0%	78.0%	84.0%
Random Forest	83.5%	81.0%	70.1%	75.2%	88.0%
AdaBoost	85.1%	83.5%	72.8%	77.8%	89.0%


Confusion matrices, ROC curves, and feature importances are included in the results/ directory.


---

🔚 Conclusion

Churn is highly influenced by contract type, tenure, and monthly charges.

Tree-based models (especially AdaBoost, XGBoost) outperform linear models.

The model can help target high-risk customers with personalized retention offers.



---

📚 References

Kaggle - Telco Customer Churn

IBM Sample Datasets

Scikit-learn, XGBoost, Pandas, Matplotlib, Seaborn
