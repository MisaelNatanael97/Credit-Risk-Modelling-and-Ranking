# Credit Risk Modelling and Ranking

Build machine learning model which can predict whether or not a client/applicant will repay the loan or have difficulty which can lead to significant losses. This model can be helpful to the lenders to approve/reject loan application based on clients risk ranking.

There are 5 csv file here:
- train → main training dataset
- test → dataset for model testing
- prev_app → provides several information about the previous loan application of each client
- installment_payment → provides payment information of each installment related to the previous loan application of each client
- columns_description → describe every column appeared in each dataset

Some highlights in this project report:
- Exploratory data analysis (EDA)
- Clever handling missing values (not every missing values must be imputed)
- Deriving new features from another table
- Predictive model: Logistic Regression, XGBoost, LightGBM
- Risk ranking to help lenders to make decision

Just open the [credit-risk.ipynb](https://github.com/MisaelNatanael97/Credit-Risk-Modelling-and-Ranking/blob/master/credit-risk.ipynb) file (can be accessed via Google Colab).

Don't forget to download the csv files to your working directory.
