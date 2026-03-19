Phishing Website Detection using Machine Learning
This project focuses on detecting whether a website is phishing or legitimate using machine learning techniques. The model is trained on a dataset containing different features related to website characteristics such as URL, domain, SSL, and behavior.

Dataset Description 
Dataset Name: Phishing Websites Dataset
Source: UCI Machine Learning Repository
Total Instances: 11,055
Total Features: 30 input features + 1 target variable
The target variable Result indicates:
1 → Legitimate website
0 → Phishing website

Model Used: Random Forest Classifier
In this project, the Random Forest Classifier is used to classify websites as phishing or legitimate.
Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce errors.
Instead of relying on a single decision tree, Random Forest creates many trees using different subsets of the data. 
Each tree makes its own prediction, and the final output is decided based on majority voting. This makes the model more stable and reliable compared to using a single model.

Conclusion:
This study shows that machine learning can effectively detect phishing websites using the given dataset. 
The Random Forest model achieved high accuracy (~97%), proving that the features used are meaningful for classification. 
Overall, this approach can be applied in real-world cybersecurity systems to prevent phishing attacks.
