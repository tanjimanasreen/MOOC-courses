# IBM Data Science Professional Certificate 

---

## Customer Loan Status Prediction 


### Summary: 
In this project, a classification task is being performed to predict whether a loan status will be paid off or not. It is done on a historical dataset from previous loan applications. 

### Machine Learning Models:
For the predictive analysis, 4 most common traditional algorithms are being used.
- K-Nearest Neighbour 
- Decision Tree
- Support Vector Machine
- Logistic Regression

### Evaluation Metrics:
For assessing the performance of the models, these metrics are being used:
- **Jaccard Index:** Jaccard Index or Jaccard Similarity Coefficient is a statistical metric that measures the similarity between the set of predicted labels and the corresponding set of actual/true labels. The higher the score of jaccard index, the better the performance of the classification. <br/> 
```(y_true, y_pred) = |y_true Intersection y_pred| / |y_true Union y_pred|```
- **F1-Score:** It is known as the weighed average of the precision and recall of a classification model. <br/> ```F1-score = 2 * (precision * recall) / (precision + recall)```
- **Log Loss:** Log loss or cross-entropy loss is the negative average of the log of corrected predicted probabilities for each instance.