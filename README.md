# Online_Shopping_Intention_Model

 ## Analysis of Logistic Regression Model
 
 The logistic regression model predicts revenue for both the 0 and 1 labels with varying levels of accuracy. Here's a breakdown of the model's performance for each label:

For the label 0 (indicating no revenue):

Precision: 0.90
Recall: 0.97
F1-score: 0.94
This means that the model correctly predicts 90% of the instances where there is no revenue (high precision), and it captures 97% of the actual instances where there is no revenue (high recall). The F1-score combines precision and recall into a single metric, and in this case, it is 0.94. Overall, the model performs very well in predicting instances where there is no revenue.

For the label 1 (indicating revenue):

Precision: 0.73
Recall: 0.39
F1-score: 0.51
For instances where there is revenue, the model's performance is not as good. It correctly predicts 73% of the instances where there is revenue (precision), but it only captures 39% of the actual instances where there is revenue (recall). The F1-score, which considers both precision and recall, is 0.51. This indicates that the model struggles to accurately predict instances with revenue and has a higher tendency for false negatives (predicting no revenue when there is actually revenue).

In summary, the logistic regression model performs well in predicting instances without revenue (label 0), but it has lower accuracy in predicting instances with revenue (label 1). Further improvements may be necessary to enhance the model's ability to identify instances with revenue accurately.
 
 
