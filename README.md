#Handling Unbalanced data


“The idea of imputation is both seductive and dangerous” (R.J.A Little & D.B. Rubin)
We will use the Credit Card Fraud Detection Dataset available on Kaggle. The dataset is high imbalanced, with only 0.17% of transactions being classified as fraudulent. 
The Problem with Imbalanced Classes
Most machine learning algorithms work best when the number of samples in each class are about equal. This is because most algorithms are designed to maximize accuracy and reduce error.
So what can be done?

Undersampling
Oversampling
Usually undersampling is not prefferred as we loose lot of information but can be performed if we have a huge dataset.
