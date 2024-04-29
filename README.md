# MSBA CAPSTONE -  HOME CREDIT DEFAULT RISK PREDICTION 

## Business Problem & Project Objective
Home Credit is an international non-banking financial institution focusing on lending money to people without a credit history. By providing a safe and comfortable borrowing experience, Home Credit aims to increase the number of people who are not banked and their financial inclusion. The primary problem faced by Home Credit is the challenge of accurately predicting the loan-repaying capabilities of individuals with insufficient or non-existent credit histories. Hence, to make low-risk and informed lending decisions, the firm wants to use historical loan application data to predict whether an applicant can repay the loan.

## Solution 
To address the challenge of loan repayment prediction, my project uses a supervised learning framework, leveraging historically labeled data to forecast binary outcomes where '0' represents timely payment and '1' indicates repayment difficulties. I selected an ensemble method with Logistic Regression and the LGBM model, which had the most significant test AUC and Kaggle score of around 0.63. I used data sources such as application training data, bureau data, and previous application data to improve decision-making. This solution gives Home Credit a powerful tool for refining its lending strategy, powered by predictive analytics and enhanced with insights from extensive credit histories.

## Contribution to the project
My contributions to this project were extensive and critical to its completion. I proceeded with Exploratory Data Analysis and Outlier Analysis to confirm data quality, then led Feature Engineering and implemented Feature Scaling and Normalization to improve model efficiency. I preserved the Train and Test Splits and used a variety of Sampling Techniques to balance the dataset and improve prediction accuracy. In addition, I created prediction templates, offered model interpretations, and proofread and finalized our outputs to ensure clarity and precision.

## Business Values
1.	**Improved Loan Decision-Making**: Using Logistic Regression and other combined models, such as Random Forest and LGBM, will allow Home Credit to make more informed and confident loan approval decisions. Accurate predictions of loan payback behavior support this better decision-making process.
2.	**Reduced Financial Risk**: Better prediction models minimize Non-Performing Assets and financial risks by identifying potential defaulters early.
3.	**Streamlined Loan Processing**: Integrating machine learning models automates and speeds up the loan approval process, reducing operational costs and improving customer satisfaction.
4.	**Customized Financial Products**: Utilizing model outputs allows for tailored credit limits and interest rates based on individual risk assessments.
5.	**Proactive Default Management**: Predictive insights enable proactive interventions like financial counseling to mitigate risk before defaults occur.
6.	**Optimized Resource Allocation**: Accurate predictions allow for efficient resource distribution, prioritizing manual reviews for high-risk applications and streamlining approvals for low-risk ones.
7.	**Maximized Loan Repayment Rates**: By accurately predicting loan repayment behaviors, the models enable Home Credit to focus on clients most likely to fulfill their financial obligations, maximizing repayment rates and overall portfolio profitability.

## Challenges Faced
During the project, I encountered several significant challenges that impacted both the modeling process and data handling. Managing missing values took much work, as many of these columns were highly correlated with the target variable, complicating the process of data imputation without introducing bias. Additionally, tuning the Random Forest and LGBM models proved computationally demanding, often stretching our system's capabilities. The LGBM model, in particular, required careful adjustment of parameters to balance model accuracy and computational efficiency. The necessity for robust computational infrastructure became apparent, especially when handling large datasets and complex models. Furthermore, determining feature importance and conducting thorough testing to ensure the models' validity and reliability across different scenarios added complexity to the project execution.

## My learnings
This end-to-end project, from defining the business challenge to obtaining actionable data, offered a comprehensive learning experience. It allowed me to deepen my understanding of Exploratory Data Analysis and refine my Logistic Regression and Random Forest models skills. Additionally, it enriched my knowledge of advanced modeling techniques, particularly with the LGBM model, and enhanced my approach to feature engineering. A key takeaway was learning to translate technical outcomes into business values, using tools like the ROC-AUC curve and feature importance charts to communicate findings effectively. Working with massive datasets in a real-world setting was very instructive, soaking challenges and practical application opportunities. This project has fueled my enthusiasm for tackling similar complex issues in the future and has motivated me to explore further and master different business models in upcoming projects.

## Presentation link 
[Capstone Presentation](
https://github.com/CharithReddyG/Home-credit/blob/9b77cda43d1ba63702ecdfce6d198853bee36141/Capstone%20Presentation%20Group%206%20(1).pptx)

## Link to Project file 
[Project file]()
