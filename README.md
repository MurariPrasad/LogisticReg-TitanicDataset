# Survival Prediction on Titanic Dataset using Logistic Regression

**About**
- Logistic Regression is a Classification Algorithm in Machine Learning, 
thus suitable for this problem of Classifying, if a person survies or not
(0 for NO, 1 for Yes) 

**Implementation**
- The data is fetched into pandas and is preprocessed. The columns 
are cleaned of NA values and unwanted features are dropped.
- The Algorithmis implemented in 2 ways, using mathematically approached
Gradient Descent, and using a package with optization algorithms in scipy(for Conjugate Descent)
- Both approaches showed good results. But Conjugate Descent was way faster when optimization was in process
and easier to implement due to the availablity of the package.

**Result**
Gradient Descent = 80.20% 
Conjugate Descent =  80.31%