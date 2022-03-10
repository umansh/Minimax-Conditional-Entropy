# Minimax-Conditional-Entropy
The observation that workers usually have difficulty distinguishing between two adjacent 
ordinal classes whereas distinguishing between two classes which are far away from each 
other ismuch easier. The method formulate as minimax conditional entropy subject to 
constraints which encode this observation.

The method of Dawid & Skene (1979) implicitly assumes that a worker performs equally well 
across all items in acommon class. In practice, however, it is often the case that one 
item is more difficult to label than another. To address this heterogeneous issue, 
Zhou et al. (2012) propose a minimax entropy principle for crowdsourcing.

data have been generated for binary classification. The given research paper is for 
multiclass classification. i have chosen binary classification to gain knowledge 
and how given algorithm 1 works. for this purpose, the input data was converted to
ordinal data set and the output of each input was converted to binary using a label
encoder. Then empirical tensor is calculated using the entropy of the data, so that 
difference between actual and predicted output should be zero. to generate worker 
confusion matrix, different 4 methods use such as LogisticRegression,GaussianNB, 
svm, KNeighborsClassifier to achieve confusion matrix for workers. following, the 
probability of each class has been calculated from the test data set.
