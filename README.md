Source: Public Loan Prediction dataset (you can use Kaggle’s “Loan Prediction )

Features:
Gender
Married
Dependents
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Target: Loan_Status (Y/N)

Installation
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/loan-predictor-svm.git
cd loan-predictor-svm
Create a virtual environment and install dependencies:


├── data/                   # Training and testing data
├── models/                 # Saved SVM model
├── app.py                  # Streamlit web app
├── train.py                # Script to train the model
├── predict.py              # Script to predict using saved model
├── requirements.txt        # Python dependencies
└── README.md    

Model Details
Algorithm: Support Vector Machine (SVM)
Kernel: RBF or Linear (configurable)

Results
Achieved ~85% accuracy on validation data.

High precision and recall for loan approval class.
