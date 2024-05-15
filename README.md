# Credit-Default-Risk-Prediction

### Abstract
This study addresses the application of Artificial Intelligence (AI) in the finance sector, focusing on predicting credit defaults. Accurate prediction of credit defaults can prevent substantial financial losses, contributing to the stability of financial institutions and the broader economy. We explore various AI techniques, including logistic regression, decision trees, Naive Bayes, K-nearest neighbors, neural networks, Random Forest, and Gradient Boosting to determine the most effective method for this problem.

Keywords: Credit Risk, Credit Default, Finance, Random Forest, Machine Learning, K-Nearest Neighbor, Decision Tree, Naive Bayes, Logistic Regression, Random Forest, Gradient Boosting, Neural Networks

### 1. Introduction

Credit risk is the possibility of suffering a loss if a debtor defaults on a loan or a particular credit line by failing to pay the interest (Switzer and Wang 2013). The reason why we should focus on measuring default risk instead of debt valuation is because of the implicit inclusion of default risk in debt value. Default-risk measurement could be independently validated, it is sensible to concentrate on it since debt value ought to be accurate if default risk calculation is confirmed (Kealhofer 2003).  Financial institutions are now able to handle the real-time data supplied by clients more healthily thanks to analytics (Sayjadah et al. 2018). Banks may now explore a new horizon that was not conceivable with their old descriptive approach thanks to predictive and prescriptive analytics (Sayjadah et al. 2018) (Venkatesh and Jacob 2016).

Credit scoring is one of the key forecasts that banks are worried about since it helps them understand why consumers are more likely to fail (Sayjadah et al. 2018). To reduce potential losses in financial institutions, they use credit default prediction which estimates the potential default risk and rejects new credit proposals if the default risk exceeds a certain acceptance threshold (Moula et al. 2017). The productivity and profitability of financial institutions depend heavily on the accuracy of credit prediction because, as stated by (Ala'raj and Abbod 2016), even a small improvement in the accuracy of credit prediction of prospective applicants with default credit can prevent the financial industry from suffering a significant loss in the future (Moula et al. 2017). In this research, artificial intelligence (AI) approaches are presented as a sophisticated alternative that may improve accuracy in credit default prediction and adapt to new data.

### 2. The Real-World Problem

The high cost of loan default is a tragedy that is frequently seen in the credit markets (Hunte 1996). Loan default is tragic because it frequently leads to credit organizations' collapse due to a lack of implementation of sound lending practices and reliable credit policies. When the flow of payments diminishes due to default issues, lenders become welfare agencies rather than sustainable financial entities (Hunte 1996). When a credit prediction model is not advanced enough to differentiate between high-risk and low-risk applicants, it unfairly penalizes creditworthy applicants and it also undermines public confidence in formal financial markets which may lead to savers withdrawing their money from financial institutions (Hunte 1996).

A financial institution will be able to minimize the expected default or misclassification rate, given to some exogenous acceptance condition, by rating clients based on estimated default probability (Carling et al. 1998). Artificial Intelligence is the ideal answer for financial institutions worldwide who are working hard to enhance the corporate banking loan origination process in response to rising competition and bankruptcy (Özdemir and Boran 2004).

### 3. Project Aim and Objectives

This project aims to employ artificial intelligence to develop and implement a robust machine learning model that is capable of predicting credit default risk accurately to enable financial institutions to minimize financial losses through credit default.
The objectives of the project are as follows;
- Conduct a comprehensive literature review to analyze existing credit default prediction systems and existing machine learning approaches.
- Analyze borrower data to understand financial behaviors and socioeconomic impacts.
- Develop an AI model to predict loan default risk effectively.
- Evaluate various AI algorithms and select the most suitable for predicting credit defaults.
- Implement and assess the chosen AI models in real-world scenarios.

### 4. Adopted Artificial Intelligence Approach

According to prior research, various data mining methods including neural networks, linear regression, Naïve Bayes, and random forest regression, are essential for assessing customer risk and default probability (Venkatesh and Jacob 2016) (Sayjadah et al. 2018). We explored several AI algorithms and made a selection based on each algorithm's capacity to handle the nuances and complexity of credit default prediction, supported by insights from academic literature and practical assessments. The following algorithms will be used in this process;
- Logistic Regression Model: A generalized linear model called a logistic model is used to forecast the likelihood of a binary answer (Yu 2020).
- Decision Tree Model: A decision tree is a structure that resembles a flowchart and is used to handle decision analysis problems (Yu 2020).
- Naive Bayesian Model: This classifier approach was created using the Bayesian theorem, which posits that features and attributes are independent. As a result, it works well with large-dimension inputs (Wang et al. 2020).
- K Nearest Neighbours Model: The term "k-nearest neighbor" (kNN) is a technique that, using a given distance metric, locates k training samples in the training set that is closest to the given training sample (Lai 2020).
- Neural Network (Multi-layer Perceptron Model): The most popular method for examining the risk connected to credit clients was the neural network. The results of a study indicated that neural networks had the greatest processing capacity when dealing with large-scale, intricate financial data (Sayjadah et al. 2018).
- Random Forest Model: The random forest regression model employs a sequence of decision trees for prediction. According to a study by Venkatesh and Jacob (2016), the random forest approach has the highest degree of accuracy when it comes to credit card default prediction.
- Gradient Boosting Model: It is an ensemble learning technique that creates a strong classifier by combining many weak decision trees (Patel et al. 2020). 

### 5. Artificial Intelligence Approach Implementation

In 1990, Jappelli identified credit history, income, and collateral as primary influencers of credit decisions, with lesser impact from job stability and demographic factors (Özdemir and Boran 2004). Crook extended this analysis to 1989 data, finding that higher education levels enhance borrowers' credit demand and eligibility. He also noted that default likelihood decreases with age but increases with larger family sizes (Özdemir and Boran 2004). 

Comparative Insights:
The comparative analysis before and after optimizations demonstrates that:
- Feature Selection generally improves the precision of the models, which is critical in ensuring that the models do not falsely label customers as defaulters.
- Hyperparameter Tuning was particularly effective for ensemble methods, where it significantly enhanced their precision and recall.
- The enhancements in AUC post-tuning for models like Gradient Boosting indicate that these models are now better at distinguishing between classes across different settings.

Based on the results, the Gradient Boosting model showed the highest accuracy score, AUC score at approximately 0.951 which indicates that the model has a great measure of separability between the classes (default vs. non-default) and its F1-score, which balances precision and recall, is also the highest, indicating that the model maintains a good balance between catching as many defaults as possible (recall) and maintaining a low false positive rate (precision).

The ‘cb_person_default_on_file_Y’ coefficient is 0.9923 and standard error is 0.031. The positive coefficient suggests a strong relationship between having a history of default and the likelihood of defaulting again.

The ‘person_income’ coefficient is -1.962e-05, indicating a slight decrease in default probability with increasing income and ‘person_emp_length’ coefficient is -0.0270, suggesting that longer employment duration slightly reduces the default risk. 

### Conclusion and Future Work
The project successfully demonstrated the potential AI has in improving credit default predictions, with significant implications for risk management in finance. Future research could explore integrating more advanced machine learning techniques, larger datasets, and real-time prediction capabilities to further enhance accuracy and reliability.

### References
Ala’raj, M. and Abbod, M. F., 2016. Classifiers consensus system approach for credit scoring. Knowledge-Based Systems, 104, 89–105.

Carling, K., Jacobson, T. and Roszbach, K., 1998. Duration of Consumer Loans and Bank Lending Policy: Dormancy Versus Default Risk. Working Paper Series in Economics and Finance, 1–28.

Hunte, C. K., 1996. Controlling Loan Default and Improving the Lending Technology in Credit Institutions. Savings and Development [online], 20 (1), 45–59. Available from: https://www.jstor.org/stable/25830566 [Accessed 9 May 2024].

Kealhofer, S., 2003. Quantifying Credit Risk I: Default Prediction. Financial Analysts Journal, 59 (1), 30–44.

Lai, L., 2020. Loan Default Prediction with Machine Learning Techniques [online]. IEEE Xplore. Available from: https://ieeexplore.ieee.org/abstract/document/9240729.

Lutz, M., 2013. Learning Python, 5th Edition [online]. 5th ed. O’Reilly Media, Inc. Available from: https://www.oreilly.com/library/view/learning-python-5th/9781449355722/.

Moula, F. E., Guotai, C. and Abedin, M. Z., 2017. Credit default prediction modeling: an application of support vector machine. Risk Management, 19 (2), 158–187.

Ntow-Gyamfi, M. and Boateng, S. S., 2013. Credit risk and loan default among Ghanaian banks: An exploratory study. Management Science Letters, 3 (3), 753–762.

Özdemir, Ö. and Boran, L., 2004. An Empirical Investigation on Consumer Credit Default Risk [online]. www.econstor.eu. Available from: https://hdl.handle.net/10419/83237 [Accessed 9 May 2024].

Patel, B., Patil, H., Hembram, J. and Jaswal, S., 2020. Loan Default Forecasting using Data Mining [online]. IEEE Xplore. Available from: https://ieeexplore.ieee.org/abstract/document/9154100/.

Russell, S. J. and Norvig, P., 2021. Artificial intelligence: a modern approach. London: Pearson.

Sayjadah, Y., Hashem, I. A. T., Alotaibi, F. and Kasmiran, K. A., 2018. Credit Card Default Prediction using Machine Learning Techniques. 2018 Fourth International Conference on Advances in Computing, Communication & Automation (ICACCA).

Switzer, L. N. and Wang, J., 2013. Default Risk Estimation, Bank Credit Risk, and Corporate Governance. Financial Markets, Institutions & Instruments, 22 (2), 91–112.

Taiwo, J., Ucheaga, E., Achugamonu, B., Adetiloye, K., Okoye, L. and Agwu, M. E., 2017. Credit Risk Management: Implications on Bank Performance and Lending Growth. Saudi Journal of Business and Management Studies [online], 2 (2415-6671). Available from: http://scholarsmepub.com/wp-content/uploads/2017/06/SJBMS-25A468-474.pdf.

Tse, L., 2020. Credit Risk Dataset. Available from: https://www.kaggle.com/datasets/laotse/credit-risk-dataset/data.

Venkatesh, A. and Jacob, S. G., 2016. Prediction of credit-card defaulters: a Comparative Study on Performance of Classifiers. International Journal of Computer Applications, 145, 7.

Wang, Y., Zhang, Y., Lu, Y. and Yu, X., 2020. A Comparative Assessment of Credit Risk Model Based on Machine Learning ——a case study of bank loan data. Procedia Computer Science, 174, 141–149.

Yu, Y., 2020. The Application of Machine Learning Algorithms in Credit Card Default Prediction [online]. IEEE Xplore. Available from: https://ieeexplore.ieee.org/document/9275986.
