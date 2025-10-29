
**Project Title:** Bank Loan Approval Prediction using IBM SPSS Modeler

**Project Overview:**
This project aims to predict whether a loan application should be approved or rejected using the CHAID Decision Tree algorithm in IBM SPSS Modeler. The goal is to help banks automate their decision-making process based on customer details such as income, credit history, and property area.

**Objective:**
Manual loan evaluation can be time-consuming and inconsistent. This model provides a data-driven approach to identify which applicants are most likely to get loan approval, improving accuracy and efficiency in financial decision-making.

**Dataset Details:**
The dataset includes around 600+ records of applicants.
Each record has information such as:

* Gender
* Applicant income
* Loan amount
* Credit history
* Education level
* Property area
* Loan status (Approved or Rejected – this is the target variable)

**Tools Used:**

* IBM SPSS Modeler
* CHAID Decision Tree algorithm
* Data Partitioning (Train/Test split)
* Analysis Node for model evaluation
* GitHub for version control

**Process Summary:**

1. Imported the dataset into SPSS Modeler.
2. Cleaned missing or inconsistent data.
3. Defined the target field as `Loan_Status`.
4. Split data into 70% training and 30% testing.
5. Built a CHAID decision tree model.
6. Evaluated performance using the Analysis node.
7. Exported final predictions as a CSV file.

**Model Results:**

* Training accuracy: 80.5%
* Testing accuracy: 92.8%

This means the model performs well even on unseen data.

**Key Findings:**

* Credit history is the most important factor for loan approval.
* Applicants with a clean credit record and stable income are more likely to get approval.
* CHAID is useful for generating clear, easy-to-interpret decision rules.

**Folder Structure:**

* Dataset folder – contains the loan data (CSV)
* Stream file – contains the SPSS Modeler project (.str)
* Output folder – includes the prediction results
* Screenshots – workflow and output screenshots
* README file – project documentation

**Future Improvements:**

* Try Random Forest or Logistic Regression for comparison.
* Deploy the model using a simple web app (Flask or Streamlit).
* Add validation techniques to further improve accuracy.

**Author:**
Mahek Khan
Data Science & Analytics Enthusiast


