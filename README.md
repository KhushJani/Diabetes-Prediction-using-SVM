# Diabetes-Prediction-using-SVM
High blood sugar levels are a hallmark of diabetes, a chronic disease that affects many people. Since diabetes can be managed with minor drug modifications and/or lifestyle changes, early identification is crucial. Doctors can use diabetes prediction as a useful guide so they can arrange additional testing to find diabetes early.

The dataset contains several predictor factors for diabetes and an outcome. The outcome  indicates whether the person has diabetes (1) or not (0). In ML terms, these predictor factors are called features. 

In the testing phase, we can start with real-time data about a patient such as age, number of pregnancies, insulin levels, and so on. The SVM algorithm determines a 1/0 outcome about diabetes based on which side of that boundary the data falls on. 

The best hyperplane between the two classes must be discovered by the SVM algorithm in order to correctly categorise all the data points. The hyperplane that increases the margin between the two classes is the ideal one. Support Vectors are the data points, also known as vectors, that are closest to the hyperplane, giving the algorithm the name Support Vector Machines. The training dataset's Support Vectors include the most crucial data points. The dividing hyperplane would move to a different location if these data points were eliminated from the training dataset. Additionally, they are the hardest to categorise data points.

A perfect SVM analysis yields a hyperplane that precisely divides the data points into two non-overlapping classes. Perfect separation is not always feasible, though. A model that achieves perfect separation may make numerous incorrect classifications. The SVM determines the hyperplane that maximises the margin and minimises the misclassifications in these circumstances.
