Question 1  
What is the meaning of "Kernelling" in SVM?  
a) Finding a hyperplane in such a way that increases the dimensionality of a dataset.  
b) A function to reduce the dimensionality of a dataset in SVM.  
c) Mapping data into a higher dimensional space, in such a way that can change a linearly inseparable dataset into a linearly separable dataset.  
Answser: c) Mapping data into a higher dimensional space, in such a way that can change a linearly inseparable dataset into a linearly separable dataset.

Question 2  
Suppose you train an SVM and find it overfits your training data. Which of these would be a reasonable next step? Check all that apply.  
a) Increase C  
b) Increase gamma  
c) Decrease C  
d) Decrease gamma  
Answer: c) Decrease C, d) Decrease gamma

Question 3  
Let’s say we have learned a decision tree on dataset D. Consider the split learned at the root of the decision tree. Which of the following is true if one of the data points in D is removed and we re-train the tree?  
a) The split at the root will be exactly the same as before  
b) The split could be the same or could be different  
c) The split at the root will be different  
Answer: b) The split could be the same or could be different

Question 4  
When learning decision trees, smaller depth USUALLY translates to lower training error.  
a) True  
b) False  
Answer: b) False

Question 5  
Which of the following is true for decision trees?  
a) Model complexity increases with size of the data.  
b) None of the above  
c) Model complexity increases with depth.  
Answer: c) Model complexity increases with depth.

Question 6  
Pruning and early stopping in decision trees is used to  
a) None of the above  
b) Combat overfitting  
c) Improve training error  
Answer: b) Combat overfitting

Question 7  
Which of the following is NOT an ensemble method?  
a) Random forests  
b) Single decision trees  
c) Gradient boosted trees  
d) AdaBoost  
Answer: b) Single decision trees

Question 8
Each binary classifier in an ensemble makes predictions on an input x as listed in the table below. Based on the ensemble coefficients also listed in the table, what is the final ensemble model's prediction for x?
![image](https://github.com/user-attachments/assets/1332bbbe-b2b5-40bc-9090-175b9459a40e)  
a) -1  
b) +1  
Answer: a) -1

Question 9  
AdaBoost focuses on data points it incorrectly predicted by increasing those weights in the data set.  
a) True  
b) False  
Answer: a) True

Question 10  
Consider the following 2D dataset with binary labels.  
![image](https://github.com/user-attachments/assets/965d231e-eaa4-4ff4-babf-1f8722fc4d9f)  
We train a series of weak binary classifiers using AdaBoost. In one iteration, the weak binary classifier produces the decision boundary as follows:  
![image](https://github.com/user-attachments/assets/978cf070-51ec-4bfe-8942-2cfe4146dd48)  
Which of the five points (indicated in the second figure) will receive higher weight in the following iteration? Choose all that apply.  
a) 4  
b) 5  
c) 3  
d) 2  
e) 1  
Answer: c) 3, d) 2
