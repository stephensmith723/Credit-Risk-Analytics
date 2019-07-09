# Credit-Risk-Analytics

We have the following data set for credit ranking for 12 different industry sections (it is a simulated data): credit data .csv, where the first 1540 samples (rows) are labeled as ’good credit’ (label type: ’1’ ), i.e., whose credit rankings are ’AAA’, ’AA’, or ’A’ and the remain- ing 130 samples are labeled as ’bad credit’, (label type: ’0’) whose credit ranks are ’CCC’.


There are six variables (columns) in this data set:
  variable 1: Working capital / Total Assets (WC TA);
  variable 2: Retained Earnings / Total Assets (RE TA);
  variable 3: Earnings Before Interests and Taxes / Total Assets (EBIT TA); 
  variable 4: Market Value of Equity / Book Value of Total Debt (MVE BVTD); 
  variable 5: Sales / Total Assets (S TA);
  variable 6: Industry sector labels from 1-12.


Conduct k-fold (k=10) cross validation for the data and use the following prediction to con- duct classifications and compare their results:
SVM with ’linear’, ’rbf’, ’poly’, and ’sigmoid’ respectively;
Compare the support vectors under different kernels;
Compare the eigenvalues of kernel matrices under different kernels
