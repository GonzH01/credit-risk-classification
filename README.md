# Credit Risk Analysis Report
## Overview


The purpose of this analysis is to develop a machine learning model that can predict whether a loan is safe or risky based on various financial attributes of borrowers. The goal is to assist a lending company in assessing the creditworthiness of loan applicants and minimizing the risk of default.


## Results


* **Logistic Regression Model:**
    - Accuracy Score: 0.993
    - Precision Score (for label 0): 1.00
    - Precision Score (for label 1): 0.86
    - Recall Score (for label 0): 1.00
    - Recall Score (for label 1): 0.91


## Summary


The logistic regression model demonstrates strong performance in predicting both safe and risky loans. It achieves near-perfect accuracy, precision, and recall for safe loans, indicating its ability to correctly identify the vast majority of them without many mistakes. For risky loans, while the precision is slightly lower, the model still catches most of them, showing its effectiveness in flagging potential risks. Overall, this model seems well-suited for the company's needs as it effectively distinguishes between safe and risky loans, helping to mitigate the risk of default. However, it's worth noting that the model could be further improved, particularly in reducing false positives for risky loans, to enhance its overall reliability. Considering the performance of this model and its relevance to the company's goals, I recommend its use for assessing loan applications.

