# Final-Project-----ICTAK
With the rising popularity of peer-to-peer lending platforms in recent years, investors now have easy access to this alternative investment asset class by lending money to individual borrowers through platforms such as LendingClub, Prosper Marketplace, and Upstart, or to small businesses through Funding Circle. LendingClub enables investors to browse consumer loan applications containing the applicant’s credit history, loan details, employment status, and other self-reported personal information, to make determinations as to which loans to fund.
Loans from applicants deemed at higher risk of default, such as those with lower FICO credit scores, will typically carry higher interest rates and therefore the potential to yield a higher return on investment (ROI) for the investor. Conversely, lower risk-of-default loans will usually carry lower interest rates. Therefore, a machine learning model that could accurately predict the default risk of a loan using the available data on the LendingClub platform could help investors to maximize their investment returns by identifying the loans worth investing in.
This paper mainly studies the statistical analysis of historical loan data of LendingClub with the idea of imbalanced data classification and uses machine learning algorithms to establish loan default prediction model.
For this project we use data from LendingClub available publicly on Kaggle. The dataset is unbalanced since there is a significant difference in paid loans and default loans. As a result, making a prediction on such an imbalanced dataset is problematic since classifiers are prone to recognising the majority class rather than the minority class. And it results in classification’s output to be skewed. In this scenario, resolving the issue in the categorization of the unbalanced dataset is critical.
The goal of this project is to develop an end-to-end web application that helps a user to determine his chances of getting a loan. This will be done by implementing several different statistical learning techniques to try to estimate the probability of default for each loan. We use machine learning models to classify a set of unseen data and statistical metrics are used to compare the results. The finalized model will then be deployed using a flask library and a website will be created for the user to navigate and predict his chances of acquiring a loan. The following steps will be taken to create a predictive model:

1.Data exploration

2.Data preprocessing

3.Training Machine Learning Models & hyperparameter tuning

4.Implementing real-time ML predictions using the Flask API
