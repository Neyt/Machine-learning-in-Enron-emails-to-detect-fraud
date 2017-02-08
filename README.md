# Machine-learning-in-Enron-emails-to-detect-fraud
This is a project where I use machine learning to detect "People of intrest" (fraud) in the Enron scandal, based on emails that they wrote and that are now public information. 

STEPS TO SOLVE THE PROBLEM"
1) DATASET/QUESTION
  do we have enough data? enough and right features? can I define the question?
 
2) FEATURES
  Exploration (inspect correlations, outlier removal, imputatioin, cleaning)
  Creation (this about it like a human)
  Representation (text vectorization, discretization)
  Scaling (mean substraction, minmax scater, standar scater)
  Selection (KBest, Percentile, recursive, Feature elimination)
  Transformation (PCA, ICA)
  
3) ALGORITHMS
  PICKING AN ALGORITH depends if the data is labeled. 
  Is it Label?
  No. then this is unsupervised learning. We could use K-means clustering, spectal clusteing,l PCA mixture models/EM algorithms, outlier deteciton.
  Yes. then is ordered?
    yes. then this is superviced learning. Ordered or continuos output, linerar regression, Lasso regression. decision tree regeresion, SV regression
    No. discrete output. we can use decision tree, Naive Bayes, SVM, esembles, k neares neighbors, LDA, logistic regression.
    
    
