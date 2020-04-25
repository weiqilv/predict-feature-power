   
###----------------------------------------------------------------------------------------------------------------------------------------- 
 This is the instruction for running the code for the paper submitted to Pattern Recognition:
"Detecting the Distribution of Feature’s Predictive Power using Naive Bayes Classifier"

1. Place folder "PR" in your working directory

2. Change the paths of data sets and figures in code to where you define yourself


###-----------------------------------------------------------------------------------------------------------------------------------------


###----------------------------------------------------------------------------------------------------------------------------------------- 
  This document consists of four ipynb files which separately are the code of GNB, LR, WOE and RF running on jupyter notebook written by python3.5 importing many packages from anaconda an python package manager.
  
  
  DataSets:
  Each ipynb file mainly describes our method that how to use GNB(or LR/WOE/RF) to inference which range of attribute value is the best predictor of a particular class. The 8 datasets are in a range of small, medium and large datasets, across the area of Medicine, Biology, Natural Language Processing (NLP) and Computer Vision (CV), you can download the datasets from the website in the paper and put them in your local location with the code.
  
  
  The steps we do in each code:
   Each data set needs running the following six parts in order: load data set, do data preprocessing, hyperparameter tuning, fit features and labels by the method, get the posterior probability matrix and plot distributions. All you should do is executing cell by cell.


  It is important to note that if run the ipynb files without anaconda, the code will report errors without the following packages: pandas, sklearn, numpy, matplotlib.

###----------------------------------------------------------------------------------------------------------------------------------------- 



  