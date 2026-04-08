Overview

This project aims to predict whether a loan application will be approved or rejected based on applicant details such as income, credit history, loan amount, and other factors.

The model is built using machine learning techniques to automate the loan approval process and reduce manual effort.

🎯 Objective
Predict loan approval status (Approved / Not Approved)
Analyze key factors affecting loan decisions
Build a reliable ML model for classification
📂 Dataset
Source: Kaggle Loan Prediction Dataset
Features include:
Gender
Marital Status
Applicant Income
Loan Amount
Credit History
Property Area
Target variable:
Loan_Status
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook
⚙️ Project Workflow
1. Data Preprocessing
Removed unnecessary columns (Loan_ID)
Handled missing values using mode
Converted categorical data using Label Encoding
2. Data Splitting
Training data: 80%
Testing data: 20%
3. Model Building
Algorithm used: Random Forest Classifier
4. Model Evaluation
Accuracy Score
R² Score
Classification Report
📊 Results
Accuracy: ~80% (depends on dataset)
Key factor: Credit History has highest impact
💾 Model Saving

The trained model is saved as:

loan_model.pkl

This file can be used for deployment or future predictions.

📁 Project Structure
Loan_Approval_Project/
│
├── loan_data.csv
├── loan_prediction.ipynb
├── loan_model.pkl
├── README.md
└── ppt.pptx
🚀 How to Run
Clone the repository
Install dependencies:
pip install pandas numpy scikit-learn
Run the notebook:
jupyter notebook loan_prediction.ipynb
📌 Future Improvements
Use advanced models like XGBoost
Perform hyperparameter tuning
Deploy using Flask or Streamlit
❓ Conclusion

The model successfully predicts loan approval with decent accuracy.
It shows that financial and credit-related features play a major role in decision-making.