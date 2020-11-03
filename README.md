# Credit-card-fraud-detection
The purpose of this project is to leverage machine learning and find out fraudulent transactions of the credit cards. The idea is to prevent fraudulent activity only by analyzing credit card transaction data. The transaction data that has been used is highly imbalanced, having only 0.2% fraud cases. The challenge is to make a supervised model that can detect fraud transactions from normal transactions. The data can be found in the following link:

https://www.kaggle.com/mlg-ulb/creditcardfraud

• TSNE plot is used to visualize the transaction data. <br>
• An autoencoder model is trained using the data. <br>
• The encoded layer is extracted from the autoencoder as a feature extraction technique. <br> 
• The extracted features are used to train different classification models.<br>
  e.g., SVM, Logistic Regression, KNN and, Artificial Neural Network (MLP). <br>
• The best model (MLP- Multi-Layer Perceptron) is trained with dropout layers, L1 regularization and achieves AUC = 0.97. <br> 

## Before Feature Extraction:
<img src="before_feature_extraction.PNG" width="70%">

## After Feature Extraction:
<img src="after_feature_extraction.PNG" width="70%">

## Performance:
### Linear Regression:
<img src="lr_performance.PNG" width="50%">

### SVM:
<img src="svm_performance.PNG" width="50%">

### KNN:
<img src="knn_performance.PNG" width="50%">

### MLP:
<img src="mlp_performance.PNG" width="70%">

# How to run:
Please check credit-fraud-detection.ipynb for the detailed analysis.
