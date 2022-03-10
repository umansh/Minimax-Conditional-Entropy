# Minimax-Conditional-Entropy
The observation that workers usually have difficulty distinguishing between two adjacent 
ordinal classes whereas distinguishing between two classes which are far away from each 
other ismuch easier. The method formulate as minimax conditional entropy subject to 
constraints which encode this observation.

The method of Dawid & Skene (1979) implicitly assumes that a worker performs equally well 
across all items in acommon class. In practice, however, it is often the case that one 
item is more difficult to label than another. To address this heterogeneous issue, 
Zhou et al. (2012) propose a minimax entropy principle for crowdsourcing.

here, data  have generated for binary classification. The given research paper is for 
multiclass classification. i have choose binary classification for to gain knowledge 
and how given algorithem 1 works.for this purpose  the input data was convereted to 
ordinal data  set and output of each input was converted to binary using label encoder.
Then empirical tensor calculated using entropy of the data, so that  difference between
actual and predicted output should be zero. to generate worker confusion matrix, 
different 4 methods use such as LogisticRegression,GaussianNB, svm, KNeighborsClassifier
to achieve confusion matrix for worker. following, probability of ech class have been 
calculated from test data set.
