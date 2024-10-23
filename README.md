Phishing Email Detection Project
Overview
This project aims to build a classification model to detect phishing emails using several machine learning algorithms. By analyzing email text, the project classifies emails as Safe Email or Phishing Email.

The dataset used contains labeled emails, and we apply models like Random Forest, SVM, XGBoost, Logistic Regression, and MLP to ensure a robust classification with high accuracy.

Phishing_Email_Detection/
│
├── Phishing_Email.csv       # Dataset file
├──hishing-email-detection-thesis.ipynb # Jupyter Notebook with all code
├── README.md                # Project documentation


Clone the repository:

git clone <repository-url>
cd Phishing_Email_Detection

Required Libraries: If you don’t have the following libraries installed, you can manually install them:
pip install pandas matplotlib numpy scikit-learn xgboost

The dataset Phishing_Email.csv contains two key columns:

Email Text: The textual content of the email.
Email Type: A label indicating whether the email is a Safe Email or a Phishing Email.


Future Work
Implementing hyperparameter tuning for better performance.
Testing on real-world email datasets.
Deploying the model as a web service using Flask/Django.



