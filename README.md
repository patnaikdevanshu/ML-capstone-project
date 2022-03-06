# The-Best-Classifier
IBM ML with Python Capstone Project

The project consists of a Banking problem to predict if a customer going to pay or not his loan based on a historical dataset that has 346 customers whose loans are already paid off or defaulted (When the loan falls in collection status). Let me show you an example of this data set:
![image](https://user-images.githubusercontent.com/71730642/155852495-d2b7794e-881b-460e-8495-a64d484dd2f8.png)

This is a Classification Problem. In Machine Learning a classification problem is when you need to predict the class of given data points. Classes are sometimes called target labels or categories. In our case e.g. Will be the loan paid or not?
Classification belongs to the category of Supervised Learning where the targets also provided with the input data.

I used four algorithms of this category:
- K-Near Neighbour (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- Logistic Regression


Why four algorithms and not only one?

When you try to solve any machine learning problem you need to test different algorithms with the same category because you don't know which of them fit better with the problem and the dataset, so you will need to make some statistics metrics technics like:

- Jaccard Index
- F1-Score
- Log Loss


Note: These metrics apply in classification problems algorithms. There are many metrics for each problem category in machine learning. The goal is to measure the accuracy of the algorithm and choose the better of them, the most accurate, in our case predicting the label "Loan_ status": PAIDOFF or COLLECTION.

Let me show you another sample, this time is the "Final Report" about all the metrics for each algorithm that I showed to you above.
![image](https://user-images.githubusercontent.com/71730642/155852547-b91a0f85-569d-448e-93af-fa7465607e84.png)


When you have this, it is easier to choose the algorithm for your problem. 
