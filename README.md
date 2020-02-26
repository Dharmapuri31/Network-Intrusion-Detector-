# Network-Intrusion-Detector
This project aims to build a network intrusion detector, a predictive model capable of distinguishing between bad connections, called intrusions or attacks, and good normal connections. <br />

Modelled as a binary classification problem. The below models are used to detect the bad intrusions <br />
• Logistic Regression <br />
• Nearest Neighbor <br />
• Support Vector Machine <br />
• Fully-Connected Neural Networks <br />

The following python libraries have been used:

Scikit-learn <br />
NumPy <br />
Pandas <br />
MatplotLib <br />

# Dataset Used
UNSW-NB15: https://www.unsw.adfa.edu.au/australian-centre-for-cyber-security/cybersecurity/ADFA-NB15-Datasets/

# Approach 

 1) Data that is captured is generally dirty and is unfit for statistical analysis, we performed data cleaning by removing null values followed by performing one hot encoding for the categorical values and normalization for the numeric values. <br />
 
 2) In order to reduce the complexity of a model and enable the algorithm to train faster, we performed feature selection to select the top 20 features out of which 15 features are taken. <br />
 
 3) We split the data and trained each of our models, We compared our models with accuracy, F1 score, precision and recall after plotting a cofusion matrix. We analysed the ROC curves for each model.
 
 4) The neural networks were tested with different hyperparameters In order to understand how a model behaves when each of them are changed. 


