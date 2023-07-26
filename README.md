# Classification_Credit-Card-Default-Prediction
Capstone Project_Classification_Credit Card Default Prediction

📋 Introduction -

Credit cards are usually small plastic cards with a unique number attached to an account. Credit cards impose the condition that cardholders pay back the borrowed money, plus any applicable interest, as well as any additional agreed-upon charges, either in full by the billing date or over time.

📋 Dataset -

The Dataset and its attributes are described below
ID: ID of each client

LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit

SEX: Gender (1=male, 2=female)

EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

MARRIAGE: Marital status (1=married, 2=single, 3=others)

AGE: Age in years

PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,8=payment delay for eight months, 9=payment delay for nine months and above)

PAY_2: Repayment status in August, 2005 (scale same as above)

PAY_3: Repayment status in July, 2005 (scale same as above)

PAY_4: Repayment status in June, 2005 (scale same as above)

PAY_5: Repayment status in May, 2005 (scale same as above)

PAY_6: Repayment status in April, 2005 (scale same as above)

BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)

BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)

BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)

BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)

BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)

BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)

PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)

PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)

PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)

PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)

PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)

PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)

default.payment.next.month: Default payment (1=yes, 0=no)

💾 Approach Method -

Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

Data Processing:-

In this part we applied SMOTE(Synthetic Minority Oversampling Technique) as the classes were unbalanced in the dataset. Also computed features based on feature importance. PAY_SEPT_0, LIMIT_BAL were the top features.

Model Creation:-

Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

💾 Models Used -

• Logistic Regression

• Decision Tree Classifier

• Random Forest Classifier

• Support Vector Machine

• Gradient Boosting

• XG Boosting

💾 Conclusion -

From all baseline model, Random Forest classifier shows highest test accuracy and F1 score and AUC. Baseline model of Random Forest and decision tree shows huge difference in train and test accuracy which shows over fitting. After cross validation and hyper parameter tuning, XG Boost shows highest test accuracy score of 87% and AUC is 0.874. Cross validation and hyper parameter tuning certainly reduces chances of over fitting and also increases performance of model.





















