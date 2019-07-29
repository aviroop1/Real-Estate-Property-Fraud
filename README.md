# Real-Estate-Property-Fraud
 Unsupervised fraud detection model that can identify likely candidates of fraud within the NYC Department of Finance Property Valuation and Assessment database
 
 <b> Approach </b>
 In this approach, I derived relevant summarized information from the data via descriptive statistics and exploratory data analysis,  inspecting the distribution and frequency of the numerical and categorical variables. Then, I populated the inconsistent records, created new variables that would give sufficient information to distinguish between anomalies and normal records.
 
 I normalized the variables, applied dimensionality reduction to retain the most important information of the data. The first fraud score was calculated based on summation of values as a heuristic function of their z-scores. For the second model, I applied a neural network model that learned the representation of data, reconstructed it, and based on the reconstruction error, the second fraud score was calculated. Then I combined the fraud scores, rank ordered them and obtained the top fraud cases. 
 
 <b> Conclusion </b>
 The combined score produced a fraud score distribution with the vast majority of properties being ranked with a score of under 500, a very small subset receiving scores of 500 to 2200. These are the potential fraud candidates in the data. 
