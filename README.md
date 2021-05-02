# school-svm
A scikitlearn svm notebook and file for the Grad Test data analysis test

During the course of the data analysis, I decided it would be appropriate to determine if some simple machine learning could reasonably predict if a student would graduate. 

Software used:
Anaconda Data Analysis Distribution
Python pandas data analysis library
Python scikitlearn machine learning library

The Scikitlearn flowchart was used to make the descision to use a Support Vector Machine. The flowchart can be found at https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html. 

Since the output is binary, it would be considered categorical. Linear SVC would not work properly, and so traditional SVC was selected. 
SVC does not use standard Beta coefficients, like linear regression, for prediction. More information about SVC can be found at https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html#sklearn.svm.SVC
