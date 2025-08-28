# Bank-Marketing
*Objective:
          To predict whether a bank customer will subscribe to a term deposit (yes/no) based on demographic, economic, and marketing-related features, using machine learning models.
*Problem Statement:
                  Banks often run marketing campaigns to promote term deposits, but contacting all customers is costly and inefficient.The problem is to build a predictive model that:
.Identifies the customers most likely to subscribe.
.Helps the bank focus its marketing efforts on the right people.
.Reduces wasted resources and increases conversion rates.

**Results:
        From models:

1)Logistic Regression:
.Achieved reasonable accuracy and balanced precision/recall.
.Provides clear feature importance (easy to explain why predictions are made).
2)Random Forest:
.Delivered higher predictive performance than Logistic Regression.
.Captures non-linear relationships better.
.Feature importance ranking shows strong influence from variables like duration, contact, month, age, and job type.
-->LIME Explanations:
.Show how individual features (e.g., call duration, previous outcome, month of contact) contribute to each prediction.
.Confirm that duration of the last call is one of the most decisive factors in predicting subscription.

**💡 Final Insights:
1)Call duration is the strongest predictor — longer calls usually indicate a higher chance of subscription.
2)Month and contact type matter — calls in certain months and via cellular methods perform better.
3)Customer demographics (age, job, education) also influence outcomes but less than call-related factors.
4)Random Forest outperforms Logistic Regression, but Logistic Regression provides easier interpretability.
5)Using LIME explanations, the bank can justify model decisions for individual customers, making the system more transparent.

👉 Overall, the project shows that machine learning can significantly improve marketing efficiency by predicting which customers are more likely to subscribe to a term deposit.

