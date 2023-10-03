# loan-eligibility
In the scope of my project, I embarked on a comprehensive analysis aimed at assessing the performance of two prominent machine learning models: Logistic Regression and Support Vector Machines (SVM). The central objective of this analysis was to evaluate their effectiveness in predicting loan eligibility, a task of significant importance in various financial and lending contexts.

Here's a detailed breakdown of the key aspects and findings of this project:

**1. Model Evaluation:** The primary focus of this project was to compare the predictive capabilities of Logistic Regression and SVM, both of which are widely used for binary classification tasks.

**2. Evaluation Metrics:** To gauge the performance of these models, I employed several evaluation metrics, including Accuracy, Precision, Recall, and F1-Score. These metrics offer a comprehensive view of a model's predictive prowess, addressing aspects such as correctness, false positive rates, and sensitivity to positive cases.

**3. Logistic Regression's Performance:** The results unveiled that Logistic Regression displayed remarkable performance. It stood out with a notable Accuracy of 79.4%, signifying its ability to make correct predictions about loan eligibility more often than not. Furthermore, Logistic Regression boasted a Precision rate of 78.5%, indicating that when it predicted loan approval (positive outcomes), it was usually accurate. This translated to fewer instances of false positive predictions, a crucial factor in real-world lending decisions.

**4. SVM's Unique Strength:** On the other hand, Support Vector Machines (SVM) demonstrated a distinctive strength in recall, achieving a perfect score of 100.0%. This high recall suggests that SVM excelled at identifying all truly eligible loans, minimizing false negatives. However, this advantage came at the expense of precision, as indicated by its lower precision rate of 69.2%. SVM had a tendency to predict more positive outcomes (class '1'), potentially leading to a higher number of false positives.

**5. Model Behavior Analysis:** It was observed that SVM exhibited a notable inclination towards predicting positive outcomes ('1'). This particular behavior could be attributed to the dataset's imbalance or the learning patterns SVM captured from the data.

**6. Limitation in Evaluation:** An essential limitation of this project was the evaluation's confinement to the training dataset. The absence of a target variable in the test dataset prevented the validation of model performance on unseen data, which is pivotal in assessing their real-world applicability.

**7. Conclusion and Implications:** In conclusion, the project revealed that Logistic Regression, with its balanced approach and high accuracy, precision, and F1-Score, provided a robust framework for predicting loan eligibility. However, the choice between Logistic Regression and SVM should be influenced by the specific use case and the relative importance of false positives and false negatives in the context of loan approval decisions. The findings underscore the potential for further analysis, including dataset balancing techniques, to enhance the reliability of predictive models in real-world lending scenarios.

This project's insights serve as a valuable reference point for stakeholders involved in loan approval processes, offering guidance on selecting the most suitable machine learning model to meet their unique needs and objectives.
