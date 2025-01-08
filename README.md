Contributors:
Sajja Pavan.
Abstract:
The report investigates market basket analysis (MBA) using the Apriori algorithm combined with logistic regression and decision tree classification to understand item associations and customer purchasing behaviors. The study aims to aid retailers in decision-making and optimizing store layouts and promotions.

Introduction:
MBA analyzes associations between products purchased together to inform retail strategies, enhance customer satisfaction, and increase sales. The use of the Apriori algorithm is detailed, explaining its role in identifying useful association rules from transaction data.

Data Collection and Preparation:
Data Collection: Transactional records with details like item description, quantity, and customer information were collected and meticulously cleaned to remove inconsistencies.
Data Preprocessing: Transformation techniques such as converting transaction data into a binary matrix using one-hot encoding were implemented to facilitate analysis.
Methodology:
Apriori Algorithm: Used to identify frequent item sets and generate association rules with defined thresholds for support, confidence, and lift.
Predictive Models: Logistic regression and decision tree classifiers were applied to predict the confidence of association rules.
Results:
Logistic Regression: Achieved 78.57% accuracy, indicating a fair ability to differentiate between high- and low-confidence rules but with limitations in identifying low-confidence rules.
Decision Tree Classifier: Demonstrated perfect accuracy (100%), correctly classifying all instances without misclassification.
Discussions and Conclusions:
The study highlights the effectiveness of combining association rule mining with predictive models. Decision trees outperformed logistic regression in accuracy and reliability. Practical insights for retailers include optimizing inventory and creating targeted marketing campaigns based on discovered item associations.

