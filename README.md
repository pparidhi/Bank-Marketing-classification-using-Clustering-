# Bank-Marketing-classification-using-Clustering

This project involves the classification of clients subscribing to a term deposit in a Portuguese banking institution's direct marketing campaigns. The dataset, obtained from the UCI Machine Learning Repository [Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing), includes various attributes related to client information and marketing campaign details.

## Dataset

The dataset, named "bank-additional-full.csv," comprises 41188 examples with 20 input features. The classification goal is to predict whether a client will subscribe (yes/no) to a term deposit (variable y).

### Attribute Information

#### Bank Client Data
1. Age (numeric)
2. Job: Type of job (categorical)
3. Marital: Marital status (categorical)
4. Education: Education level (categorical)
5. Default: Has credit in default? (categorical)
6. Housing: Has housing loan? (categorical)
7. Loan: Has a personal loan? (categorical)

#### Last Contact of the Current Campaign
8. Contact: Contact communication type (categorical)
9. Month: Last contact month of the year (categorical)
10. Day_of_week: Last contact day of the week (categorical)
11. Duration: Last contact duration in seconds (numeric) 

#### Other Attributes
12. Campaign: Number of contacts performed during this campaign and for this client (numeric)
13. Pdays: Number of days since the client was last contacted from a previous campaign (numeric)
14. Previous: Number of contacts performed before this campaign and for this client (numeric)
15. Poutcome: Outcome of the previous marketing campaign (categorical)

#### Social and Economic Context Attributes
16. Emp.var.rate: Employment variation rate - quarterly indicator (numeric)
17. Cons.price.idx: Consumer price index - monthly indicator (numeric)
18. Cons.conf.idx: Consumer confidence index - monthly indicator (numeric)
19. Euribor3m: Euribor 3-month rate - daily indicator (numeric)
20. Nr.employed: Number of employees - quarterly indicator (numeric)

#### Output Variable
21. Y: Has the client subscribed a term deposit? (binary: 'yes', 'no')

## Problem Definition

The problem is approached through clustering using K-means and Fuzzy-c-mean algorithms. The goal is to evaluate the classification performance using 5-fold cross-validation.

## Evaluation Metrics

The clustering performance is assessed using the following evaluation metrics:

- Confusion Matrix
- Sensitivity
- Specificity
- Total Accuracy
- F1-Score
- ROC Curve
- Area Under Curve (AUC)

## Results

The results of the clustering algorithms during 5-fold cross-validation are presented, including the confusion matrix, sensitivity, specificity, total accuracy, F1-score, ROC curve, and area under the curve.

## Dependencies

To run the code and explore the results, ensure you have the following dependencies installed:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
