# Credit-card-fraud-detection
Understanding the Problem

• For financial banks around the world, identifying credit card fraud is crucial. Banks have to spot potential fraud so that their costumers don't pay for goods they haven't purchased. This is important so that the customer doesn't lose money and the bank does not lose its customers.

• Hence, the ultimate goal is to tackle this situation by building generalized classification models which tracks the pattern of all the transactions to classify and distinguish fraud transactions from the normal ones.

• This is a binary classification problem.
# About the Dataset
• The dataset consists of 31 feature columns and 284807 rows. Due to security issues, 28 of the features are the result of the PCA transformation. 'Time' and 'Amount are the only columns that were not modified with PCA. The output variable is named 'Class'.

• There are no null/missing values in this dataset. All feature columns are float64 or int64 values. The output variable is heavily imbalanced.

![WhatsApp Image 2022-05-05 at 9 55 13 AM](https://user-images.githubusercontent.com/79190114/166863747-3291e00b-9771-49bc-a1c1-8b43dbefa24c.jpeg)
# To get the best result I have to balance the data first.
![WhatsApp Image 2022-05-05 at 10 02 17 AM](https://user-images.githubusercontent.com/79190114/166863998-a86b758e-1d21-45a8-8e98-58da290cd041.jpeg)

Algorithm used for classification

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Ensembling techniques – Stacking, Boosting
5. Naïve Bayes
6. KNN

## Top performing model
1. Naive Bayes

![WhatsApp Image 2022-05-05 at 10 22 12 AM](https://user-images.githubusercontent.com/79190114/166865388-b249d684-08c6-45f5-8a78-4fd729550a17.jpeg)

2. Random Forest Classifier

![WhatsApp Image 2022-05-05 at 10 20 24 AM (1)](https://user-images.githubusercontent.com/79190114/166865510-cf41322c-2b83-4ab2-a802-1225c5abe48a.jpeg)

3.K-Neighbour Nearest

![WhatsApp Image 2022-05-05 at 10 20 24 AM](https://user-images.githubusercontent.com/79190114/166865644-112f1e06-0f84-47f2-b251-c86be27e2827.jpeg)

Summary
• Accuracy of Naive Bayes model is: 0.93

• Recall value : 0.89

• F1 score: 0.93

• Accuracy of Random Forest Classifier : 0.93

• Recall value: 0.89

• F1 score: 0.93

• Stacking and Random forest algorithms also performed well after some hyper-parameter tuning.

## Conclusion
• In this machine learning project, a binary classifier was implemented using various classification algorithms to predict potential fraud transactions. Through this project, several techniques were applied to address feature selection, check correlation and treat major class imbalance problem.

• 28 features columns out of 31 are the result of the PCA transformation. The output variable is named 'Class'. Visualizing data distribution with respect to time and frequency was necessary. However, the dataset was heavily imbalanced. Only 0.17% of all transactions were fraudulent.

## Results
• Looking at model results, the best accuracy on the test set was achieved by the K-Neighbour classifier algorithms followed by Logistic Regression. After that I got similar accuracy from Naive Bays and Random Forest. Which shows that my dataset is perfectly balanced and accurate




